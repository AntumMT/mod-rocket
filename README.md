# Space Shuttles Mod

Luanti has many great space mods that add in outer space thousands of blocks above the player.
However, none of them have a good way to reach outer space-- until now. With this mod, you can craft
rockets / space shuttles and fly them into and in outer space.

The forum topic for this mod is [here][forum]. There, you can find a list of crafting recipes.

## Controls overview

### Vertical mode

* A -- yaw left
* D -- yaw right
* W -- go forwards
* S -- go backwards
* Space -- move/accelerate upwards
* Space+Shift -- enable cruise mode
* Shift -- disable cruise mode
* A+D -- switch to horizontal mode

### Horizontal mode

* A -- yaw left
* D -- yaw right
* W -- move/accelerate forwards
* S -- brake
* Space -- go upwards
* Shift -- go downwards
* W+S -- enable cruise mode
* S -- disable cruise mode
* A+D -- switch to vertical mode

## Controls explained

The space shuttle has two modes: vertical mode and horizontal mode. In vertical mode, the rocket is
upright, and in horizontal mode it is sideways. Vertical mode is used for lift off and for landing,
whereas horizontal mode is used for moving and docking in outer space.

Place a Space Shuttle item down to place a space shuttle vehicle. A space shuttle will be placed in
vertical mode. Right click on the space shuttle to enter/exit.

The space shuttle has a life support system (provides you with oxygen), so you will be able to
breath in the rocket in space or an unbreathable atmosphere.

I strongly recommend that you always use 3rd person mode when riding a rocket. Also, if you crash
into something at a high velocity, then your rocket explodes.

### Vertical mode

You can move horizontally in vertical mode. Use A to yaw (turn) left, D to yaw right, W to go
forwards in the direction you have yawed, and S to go backwards in that direction. These horizontal
controls are not fast and exist mainly to make small adjustments in position; the main focus of
vertical mode is moving or falling vertically.

Hold space to move/accelerate upwards. At first, you will only move slightly up, but if you hold
long enough then you will travel at exhilerating speeds. If you need to go down or slow down, let go
of space. In vertical mode, rockets are affected by gravity, so whenever they stop going up, they go
down. If you let go of space after holding it for a while, it will seem like you are still flying
upwards. However, you are actually just coasting and your velocity is decelerating. The rocket will
decelerate until it stops going and starts going down. You go down slow at first but you go faster
and faster until you reach terminal velocity. To stop falling, hold space for a while. Although it
may seem like you are still falling, you are actually slowing your descent. You will be able to slow
your descent to the point that you are no longer falling and you are ascending again. If you use the
space button wisely, you can rise or fall at whatever speed you choose. For example, you can use
your rocket like a lunar lander if you thrust a little bit while you fall.

Press space and shift at the same time to enable vertical cruise mode, and press shift by itself to
disable it. Cruise mode automatically maintains your vertical velocity, rising or falling.

Press A and D at the same time to switch to horizontal mode. You have to slow down the rocket to
switch modes. After pressing A and D, right click once. If your head sticks out of the horizontal
rocket, right click again twice very quickly to fix the glitch.

### Horizontal mode

Unlike vertical mode, where the focus is on vertical movement, horizontal mode is focused on
movement in all directions, but mainly forwards. Also unlike vertical mode, which is affected by
gravity, horizontal mode is gravity free, since it is designed to work in space.

Use A to yaw (turn) left, D to yaw right, W to move/accelerate forwards in the direction you have
yawed, and S to brake. Hold W for a while to accelerate your forwards velocity, and S to slow down.
S cannot be used to go backwards; instead, turn the rocket around and go forwards in the new
direction.

Press W and S at the same time to enable horizontal cruise mode, and press S by itself to disable
it. Horizontal cruise mode works just like the cruise mode in the airboat mod.

Press space to go up and shift to go down. You cannot travel vertically nearly as fast as vertical
mode, but horizontal mode is still useful for vertical movement.

Press A and D at the same time to switch to vertical mode. You have to slow down the rocket to
switch modes. After pressing A and D, right click once. To avoid any potential glitches, right click
again twice very quickly. Be prepared to be affected by gravity again after you right click the
first time.

## Inspirations

* Kerbal Space Program (video game)
* Galacticraft (Minecraft mod)

## Dependencies

Required:

* [bucket](https://github.com/minetest-game/bucket)
* [default](https://github.com/minetest-game/default)
* [fire](https://github.com/minetest-game/fire)
* [stairs](https://github.com/minetest-game/stairs)
* [tnt](https://github.com/minetest-game/tnt)

Optional:

* [other_worlds](https://content.luanti.org/packages/TenPlus1/other_worlds/)
* [vacuum](https://forum.luanti.org/viewtopic.php?t=20195)

## Licensing

This mod and two models were made by [Red_King_Cyclops], but several textures and much of code was
made by other users. Almost all of the code is modified code from [Paramat's airboat mod][airboat].

Code ([MIT](LICENSE.txt)):

- [paramat] ([MIT](https://github.com/paramat/airboat/blob/master/license.txt))
- [Red_King_Cyclops] ([MIT](https://git.minetest.land/Red_King_Cyclops/rocket/src/branch/master/LICENSE))

Textures:

- [old_rocket](textures/old_rocket.png)
    - [CC BY-SA 4.0]
    - by [krokoschlange]
    - from [submarines modpack][submarines] (renamed from "submarine.png")
- [rocket](textures/rocket.png) &amp; [rover](textures/rover.png)
    - [CC BY-NC-SA]
    - by [Melkor]
- [rocket_boom](textures/rocket_boom.png)
    - [CC BY-SA 3.0]
    - by [BlockMen]
    - from [tnt] (renamed from "tnt_boom.png")
- [rocket_bucket_oil](textures/rocket_bucket_oil.png)
    - [CC BY-SA 3.0]
    - by [ElementW]
    - from [bucket] (modified version of "bucket_water.png")
- [rocket_bucket_rocket_fuel](textures/rocket_bucket_rocket_fuel.png)
    - [CC BY-SA 3.0]
    - by [ElementW]
    - from [bucket] (modified version of "bucket_water.png")
- [rocket_cone](textures/rocket_cone.png)
    - _\* licensing info is unclear_
    - ???
    - by [Red_King_Cyclops]
- [rocket_hull](textures/rocket_hull.png)
    - [CC BY-SA 3.0]
    - by [kilbith (jp)][kilbith]
    - from [default] (renamed from "default_steel_block.png")
- [rocket_left_fin](textures/rocket_left_fin.png) &amp; [rocket_right_fin](textures/rocket_right_fin.png)
    - _\* licensing info is unclear_
    - ???
    - by [Red_King_Cyclops]
- [rocket_oil_flowing_animated](textures/rocket_oil_flowing_animated.png)
    - _\* licensing &amp; author info is unclear_
    - [LGPL 2.1]
    - by [ShadMOrdre]
    - from [lib_materials] (renamed from "lib_materials_fluid_oil_flowing_animated.png")
- [rocket_oil_source](textures/rocket_oil_source.png)
    - _\* licensing &amp; author info is unclear_
    - [LGPL 2.1]
    - by [ShadMOrdre]
    - from [lib_materials] (renamed from "lib_materials_fluid_oil_source.png")
- [rocket_oil_source_animated](textures/rocket_oil_source_animated.png)
    - _\* licensing &amp; author info is unclear_
    - [LGPL 2.1]
    - by [ShadMOrdre]
    - from [lib_materials] (renamed from "lib_materials_fluid_oil_source_animated.png")
- [rocket_rocket_inv](textures/rocket_rocket_inv.png)
    - _\* licensing info is unclear_
    - ???
    - by [Red_King_Cyclops]
- [rocket_smoke](textures/rocket_smoke.png):
    - [CC BY-SA 3.0]
    - by [ShadowNinja]
    - from [tnt] (renamed from "tnt_smoke.png")
- [rocket_thruster](textures/rocket_thruster.png)
    - _\* licensing info is unclear_
    - ???
    - by [Red_King_Cyclops]


The rocket fuel textures (including the rocket fuel bucket texture) are modified water textures from
[default] and [bucket].

- [rocket_rocket_fuel_flowing_animated](textures/rocket_rocket_fuel_flowing_animated.png)
- [rocket_rocket_fuel_source](textures/rocket_rocket_fuel_source.png)
- [rocket_rocket_fuel_source_animated](textures/rocket_rocket_fuel_source_animated.png)



Models:

- [old_rocket](models/old_rocket.obj) &amp; [old_sideways_rocket](models/old_sideways_rocket.obj)
    - _\* licensing info is unclear_
    - ???
    - by [Red_King_Cyclops]
- [rocket](models/rocket.obj), [rover](models/rover.obj), &amp; [sideways_rocket](models/sideways_rocket.obj)
    - [CC BY-NC-SA]
    - by [Melkor]

For more information on Melkor's models and textures, please go
[here](https://forum.luanti.org/viewtopic.php?p=362717#p362717).

Sound:

- [thrust](sounds/thrust.ogg)
    - [CC BY 3.0]
    - by [Dynamicell](https://www.freesound.org/people/Dynamicell/sounds/17548/)
    - from [fire] (renamed from "fire_fire.3.ogg")

## Links

- [Forum][forum]
- Git Repo Mirrors:
    - [Codeberg](https://codeberg.org/AntumLuanti/mod-rocket)
    - [GitHub](https://github.com/AntumMT/mod-rocket)
    - [GitLab](https://gitlab.com/AntumMT/mod-rocket)
- [Original Mod by Red_King_Cyclops](https://git.minetest.land/Red_King_Cyclops/rocket)

## TODO

- make other_worlds compatible
- fix rover
- make rover craftable
- make new version downloadable
- update forum topic
- figure out licensing for media created by Red_King_Cyclops &amp; for rocket_fuel textures


[forum]: https://forum.luanti.org/viewtopic.php?t=23120

[airboat]: https://forum.luanti.org/viewtopic.php?t=20485
[bucket]: https://github.com/minetest-game/bucket
[default]: https://github.com/minetest-game/default
[fire]: https://github.com/minetest-game/fire
[lib_materials]: https://forum.luanti.org/viewtopic.php?p=349384
[submarines]: https://forum.luanti.org/viewtopic.php?t=16282
[tnt]: https://github.com/minetest-game/tnt

[BlockMen]: https://forum.luanti.org/memberlist.php?mode=viewprofile&u=4473
[ElementW]: https://github.com/ElementW
[kilbith]: https://content.luanti.org/users/jp/
[krokoschlange]: https://forum.luanti.org/memberlist.php?mode=viewprofile&u=19619
[Melkor]: https://forum.luanti.org/memberlist.php?mode=viewprofile&u=301
[paramat]: https://content.luanti.org/users/paramat/
[Red_King_Cyclops]: https://content.luanti.org/users/Red_King_Cyclops/
[ShadMOrdre]: https://forum.luanti.org/memberlist.php?mode=viewprofile&u=12292
[ShadowNinja]: https://content.luanti.org/users/ShadowNinja/

[CC BY 3.0]: https://creativecommons.org/licenses/by/3.0/
[CC BY-NC-SA]: https://creativecommons.org/licenses/by-nc-sa/4.0/
[CC BY-SA 3.0]: https://creativecommons.org/licenses/by-sa/3.0/
[CC BY-SA 4.0]: https://creativecommons.org/licenses/by-sa/4.0/
[LGPL 2.1]: https://www.gnu.org/licenses/old-licenses/lgpl-2.1.html
