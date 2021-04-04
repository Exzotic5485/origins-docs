---
title: Status Effect Instance (Data Type)
date: 2021-04-04
---
# Status Effect Instance

[Data Type](../data_types.md).

An [Object](object.md) used to define a status effect with duration, amplifier, etc.

### Fields

Field  | Type | Default | Description
-------|-----|---------------|-------------
`effect` | [Identifier](identifier.md) | | ID of the status effect.
`duration` | [Integer](integer.md) | 100 | Duration of the status effect in ticks.
`amplifier` | [Integer](integer.md) | 0 | Amplifier of the status effect.
`is_ambient` | [Boolean](boolean.md) | false | Whether the effect counts as an ambient effect.
`show_particles` | [Boolean](boolean.md) | true | Whether the status effect will spawn particles on the player.
`show_icon` | [Boolean](boolean.md) | true | Whether the status effect will show an icon on the HUD.

### Examples

```json
{
	"field_name": {
		"effect": "minecraft:slowness",
		"amplifier": 1,
		"duration": 80
	}
}
```
A Slowness II status which lasts for 4 seconds.

```json
{
	"field_name": {
		"effect": "minecraft:levitation",
		"duration": 200,
		"is_ambient": true,
		"show_particles": false,
		"show_icon": false,
	}
}
```
An ambient and mostly hidden status effect of Levitation I which lasts for 10 seconds.