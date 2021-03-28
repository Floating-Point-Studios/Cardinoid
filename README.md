# Cardinoid
 
Cardinoid is the [CardinalEngine](https://github.com/Floating-Point-Studios/CardinalEngine/) implementation of [Luanoid](https://github.com/LPGhatguy/luanoid).

## Usage

More detailed documentation will be available at a later date.

Any rigged character such as ones created by the "Rig Builder" plugin in Studio can be mounted to Cardinoid with the `MountRig(rig)` method. To unmount the rig use `UnmountRig()`.

Animations can be loaded through `LoadAnimation(animation, name?)`, multiple animations can be loaded under the same name. If the name matches a CharacterState that animation will play when Cardinoid enters that state. Animations can be played with `PlayAnimation(name, ...)` if multiple animations exist under that name one will be selected randomly. Animations can be stopped with `StopAnimation(name, ...)`.