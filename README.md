# Drawccoon Render Engine
### as used in [Paths of Savage Gods](https://www.kickstarter.com/projects/lyniat-games/paths-of-savage-gods)

![Waschi the drawccoon](/readme/drawccoon.png)

## About DRE
DRE is a Unity plugin for rendering huge isometric tilemaps at high performance.
E.g. maps with 16384 x 16384 tiles (one tile high) runs with 60+FPS on an average gaming pc.
But you can also render three dimensional tilemaps easily. For PoSG we use 256*256*64 tiles (we choose 256 so that we can store coordinates in one byte) but larger maps are alsno no problems.
Currently the most limiting factor is VRAM.
For more infos see the QAs.

## Where is the code?
Coming soon! (mid February)
We're just very busy with our Kickstarter campaign right now.

## Contribute and support
- You can help us realize [PoSG](https://savage-gods.com/) by contributing to our code and help fixing bugs.
- Or even better: Support us on [Kickstarter](https://www.kickstarter.com/projects/lyniat-games/paths-of-savage-gods)

## QAs
#### Why is this part of the project open source and the others are not?
Since we have to earn money for our jobs, we can't open source everything but we want to give a great piece of software and it's code back to our community and in cause of Unitys bad tile rendering we decided that this might be the most helpfull pice of code.

#### Which programming language is this written in?
Most of the rendering code is written in HLSL but the shader linker and some other parts are written in C#.

#### What are your coding conventions?
We will publish our conventions and guides together with the code!

#### Who maintaines this repository?
It's maintained by [lyniat](https://github.com/Lyniat) and [lyniat.games GmbH](https://lyniat.games).
