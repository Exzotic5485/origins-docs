---
title: Damage Source Names (Extras)
date: 2021-06-23
---

#   Damage Source Names

Damage Source Names are [strings](../../types/data_types/string.md) used for classifying what type of damage is taken/given, and to determine the death message for the damage upon being killed.

***(Hovering the cursor over the damage source names will reveal its death message.)***


### List of vanilla damage source names

Name | Description
-----|------------
[`anvil.player`](## "<victim> was squashed by a falling anvil whilst fighting <player/mob>") | Being hit by a falling Anvil while fighting a player/mob.
[`anvil`](## "<victim> was squashed by a falling anvil") | Being hit by a falling Anvil.
[`arrow.item`](## "<victim> was shot by <player/mob> using <item>") | Being shot by a player/mob using a renamed Bow or Crossbow.
[`arrow`](## "<victim> was shot by <player/mob>") | Being shot by a player/mob.
[`badRespawnPoint`](https://bugs.mojang.com/browse/MCPE-28723 "<victim> was killed by [Intentional Game Design]") | Being hit by an explosion caused by Beds from attempting to use it in The End, The Nether or custom dimensions that has Beds disabled.
[`cactus.player`](## "<victim> walked into a cactus whilst trying to escape <player/mob>") | Making contact with a Cactus while fighting a player/mob.
[`cactus`](## "<victim> was pricked to death") | Making contact with a Cactus.
[`cramming.player`](## "<victim> was squashed by <player/mob>") | Being in the same spot as many other entities while fighting a player/mob.
[`cramming`](## "<victim> was squished too much") | Being in the same spot as many other entities.
[`dragonBreath.player`](## "<victim> was roasted in dragon breath by <player/mob>") | Being damaged by the Dragon's breath while fighting a player/mob. **Unused in vanilla.** (Dragon breath deals `magic` damage).
[`dragonBreath`](## "<victim> was roasted in dragon breath") | Being damaged by the Dragon's breath. **Unused in vanilla.** (Dragon breath deals `magic` damage).
[`drown.player`](## "<victim> drowned whilst trying to escape <player/mob>") | Drowning while fighting a player/mob.
[`drown`](## "<victim> drowned") | Drowning.
[`dryout.player`](## "<victim> died from dehydration whilst trying to escape <player/mob>") | Drying out while fighting a player/mob. **Unused in vanilla.**
[`dryout`](## "<victim> died from dehydration") | Drying out. **Unused in vanilla.**
[`even_more_magic`](## "<victim> was killed by even more magic") | If the death message is too large to send. **Unused in vanilla.**
[`explosion.player`](## "<victim> was blown up by <player/mob>") | Being hit by an explosion from a mob that explodes or TNT lit by a player/mob.
[`explosion`](## "<victim> blew up") | Being hit by a regular explosion.
[`fall.player`](## "<victim> hit the ground too hard whilst trying to escape <player/mob>") | Falling from a high place while fighting a player/mob.
[`fall`](## "<victim> hit the ground too hard") | Falling from a high place.
[`fallingBlock.player`](## "<victim> was squashed by a falling block whilst fighting <player/mob>") | Being hit by a falling block that's not an Anvil block while fighting a player/mob.
[`fallingBlock`](## "<victim> was squashed by a falling block") | Being hit by a falling block that's not an Anvil block.
[`fallingStalactite.player`](## "<victim> was skewered by a falling stalactite whilst fighting <player/mob>") | Being hit by a falling Stalactite block while fighting a player/mob.
[`fallingStalactite`](## "<victim> was skewered by a falling stalactite") | Being hit by a falling Stalactite block.
[`fireball.item`](## "<victim> was fireballed by <player/mob> using <item>") | Being hit by a fireball shot by a player/mob holding a renamed item.
[`fireball`](## "<victim> was fireballed by <player/mob>") | Being hit by a fireball shot by a player/mob.
[`fireworks.item`](## "<victim> went off with a bang due to a firework fired from <item> by <player/mob>") | Being hit by a firework explosion of a firework rocket shot by a player/mob using a renamed Crossbow.
[`fireworks.player`](## "<victim> went off with a bang whilst fighting <player/mob>") | Being hit by a firework explosion of a firework rocket while fighting with a player/mob.
[`fireworks`](## "<victim> went off with a bang") | Being hit by a firework explosion of a firework rocket.
[`flyIntoWall.player`](## "<victim> experienced kinetic energy whilst trying to escape <player/mob>") | Flying into a wall at high speed using an Elytra while fighting a player/mob.
[`flyIntoWall`](## "<victim> experienced kinetic energy") | Flying into a wall at high speed using an Elytra.
[`freeze.player`](## "<victim> was frozen to death by <player/mob>") | Being in Powder Snow for too long while fighting a player/mob.
[`freeze`](## "<victim> froze to death") | Being in Powder Snow for too long.
[`generic.player`](## "<victim> died because of <player/mob") | Being damaged by a damage source which doesn't have a specific type while fighting a player/mob.
[`generic`](## "<victim> died") | Being damaged by a damage source which doesn't have a specific type.
[`hotFloor.player`](## "<victim> walked into danger zone due to <player/mob>") | Standing on Magma while fighting a player/mob.
[`hotFloor`](## "<victim> discovered the floor was lava") | Standing on Magma.
[`indirectMagic.item`](## "<victim> was killed by <player/mob> using <item>") | Being damaged by a damage source considered as indirect magic damage such as from thrown Splash Potions whilst fighting a player/mob holding a renamed item.
[`indirectMagic`](## "<victim> was killed by <player/mob> using magic") | Being damaged by a damage source considered as indirect magic damage such as from thrown Splash Potions.
[`inFire.player`](## "<victim> walked into fire whilst fighting <player/mob>") | Standing inside Fire whilst fighting a player/mob.
[`inFire`](## "<victim> went up in flames") | Standing inside Fire.
[`inWall.player`](## "<victim> suffocated in a wall whilst fighting <player/mob>") | Being inside a solid block while fighting a player/mob.
[`inWall`](## "<victim> suffocated in a wall") | Being inside a solid block.
[`lava.player`](## "<victim> tried to swim in lava to escape <player/mob>") | Being in Lava while fighting a player/mob.
[`lava`](## "<victim> tried to swim in lava") | Being in Lava.
[`lightningBolt.player`](## "<victim> was struck by a lightning bolt whilst fighting <player/mob") | Being struck by a Lightning Bolt while fighting a player/mob.
[`lightningBolt`](## "<victim> was struck by a lightning bolt") | Being struck by a Lightning Bolt.
[`magic.player`](## "<victim> was killed by magic whilst trying to escape <player/mob>") | Being damaged by a damage source considered as magic damage such as from Conduits or harmful status effects like Instant Damage or Poison while fighting a player/mob.
[`magic`](## "<victim> was killed by magic") | Being damaged by a damage source considered as magic damage such as from Conduits or harmful status effects like Instant Damage or Poison.
[`mob.item`](## "<victim> was slain by <mob> using <item>") | Being hit by a mob holding a renamed item.
[`mob`](## "<victim> was slain by <mob>") | Being hit by a mob.
[`onFire.player`](## "<victim> burned to a crisp whilst fighting <player/mob>") | Burning while fighting a player/mob.
[`onFire`](## "<victim> burned to death") | Burning.
[`outOfWorld.player`](## "<victim> didn't want to live in the same world as <player/mob>") | Falling into the void while fighting a player/mob.
[`outOfWorld`](## "<victim> fell out of the world") | Falling into the void.
[`player.item`](## "<victim> was slain by <player> using <item>") | Being hit by a player holding a renamed item.
[`player`](## "<victim> was slain by <player>") | Being hit by a player.
[`stalagmite.player`](## "<victim> was impaled on a stalagmite whilst fighting <player/mob>") | Falling onto a Stalagmite while fighting a player/mob.
[`stalagmite`](## "<victim> was impaled on a stalagmite") | Falling onto a Stalagmite.
[`starve.player`](## "<victim> starved to death whilst fighting <player/mob>") | Being damaged by starvation while fighting a player/mob.
[`starve`](## "<victim> starved to death") | Being damaged by starvation.
[`sting.item`](## "death.attack.sting.item") | Being stung by a bee holding a renamed item. **Unused in vanilla.**
[`sting.player`](## "<victim> was stung to death by <player/mob>") | Being stung by a player/mob. **Unused in vanilla.**
[`sting`](## "<victim> was stung to death") | Being stung by a bee.
[`sweetBerryBush.player`](## "<victim> was poked to death by a sweet berry bush whilst trying to escape <player/mob>") | Walking through a Sweet Berry Bush while fighting a player/mob.
[`sweetBerryBush`](## "<victim> was poked to death by a sweet berry bush") | Walking through a Sweet Berry Bush.
[`thorns.item`](## "<victim> was killed by <item> trying to hurt <player/mob>") | Hitting a player/mob that is wearing an armor with the Thorns enchantment, and holding a renamed item. Also applies to hurting Guardians/Elder Guardians.
[`thorns`](## "<victim> was killed trying to hurt <player/mob>") | Hitting a player/mob that is wearing an armor with the Thorns enchantment. Also applies to hurting Guardians/Elder Guardians.
[`thrown.item`](## "<victim> was pummeled by <player/mob>") | Being hit by a projectile thrown by a player/mob. **Unused in vanilla.**
[`trident.item`](## "<victim> was impaled by <player/mob> using <item>") | Being hit by a Trident thrown by a player/mob holding a renamed item.
[`trident`](## "<victim> was impaled by <player/mob>") | Being hit by a Trident thrown by a player/mob.
[`wither.player`](## "<victim> withered away whilst fighting <player/mob>") | Being damaged by the Wither status effect while fighting a player/mob.
[`wither`](## "<victim> withered away") | Being damaged by the Wither status effect.
[`witherSkull`](## "<victim> was shot by a skull from <player/mob>") | Being hit by a Wither Skull shot by a player/mob.


### List of Origins damage source names

Name | Description
-----|------------
[`genericDamageOverTime.player`](## "<victim> died to damage over time effect whilst fighting <player/mob>") | Being damaged by a power that uses the `origins:damage_over_time` power type with no specified damage source name while fighting a player/mob.
[`genericDamageOverTime`](## "<victim> died to damage over time effect") | Being damaged by a power that uses the `origins:damage_over_time` power type with no specified damage source name.
[`hurt_by_water.player`](## "<victim> was put underwater by <player/mob>") | Being damaged by the `origins:water_vulnerability` power whilst fighting a player/mob.
[`hurt_by_water`](## "<victim> took a bath for too long") | Being damaged by the `origins:water_vulnerability` power.
[`no_water_for_gills.player`](## "<victim> didn't manage to get wet because they were fighting <player/mob>") | Losing air with the `origins:water_breathing` power while fighting a player/mob.
[`no_water_for_gills`](## "<victim> didn't manage to keep wet") | Losing air with the `origins:water_breathing` power.
