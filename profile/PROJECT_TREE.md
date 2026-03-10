# Omicronde Project Tree

[[Back to Home](https://github.com/galaxaris)]

_Tree made the 10/03/2026_

These files are all the one currently used in the project. It is organized into several repositories:

- `api` : _Omicronde_ Game Engine & API code: core of the project, based on modularity and reusability with OOP. Using Python and Pygame.
- `game` : The actual Omicronde Project, using the API.
- `editor` : A level editor for Omicronde, using the API. Also uses Tkinter for the UI.
- `art-department` : All the art assets, music and sound effects used in the project.
- `.github/profile` : Galaxaris Organization' GitHub profile, including this project tree and a README.

_Copyright © 2026 Galaxaris & Associates. All rights reserved._

## Simplified project tree

```
C:.
├───.github
│   └───profile
├───api
│   ├───assets
│   ├───engine
│   ├───entity
│   ├───environment
│   ├───items
│   ├───physics
│   ├───UI
│   ├───utils
├───art-department
│   ├───Graphisms
│   │   ├───Backgrounds
│   │   │   ├───Pixel-Art Background 1
│   │   │   ├───Pixel-Art Background 2
│   │   │   ├───Pixel-Art Background 3
│   │   │   └───Pixel-Art Background 4
│   │   ├───Items
│   │   │   ├───Bushes
│   │   │   │   ├───Bush 1
│   │   │   │   ├───Bush 10
│   │   │   │   ├───Bush 11
│   │   │   │   ├───Bush 12
│   │   │   │   ├───Bush 13
│   │   │   │   ├───Bush 14
│   │   │   │   ├───Bush 15
│   │   │   │   ├───Bush 2
│   │   │   │   ├───Bush 3
│   │   │   │   ├───Bush 4
│   │   │   │   ├───Bush 5
│   │   │   │   ├───Bush 6
│   │   │   │   ├───Bush 7
│   │   │   │   ├───Bush 8
│   │   │   │   └───Bush 9
│   │   │   ├───Inventory
│   │   │   │   ├───Equipment
│   │   │   │   ├───Food
│   │   │   │   ├───Material
│   │   │   │   ├───Misc
│   │   │   │   ├───Monster Part
│   │   │   │   ├───Ore & Gem
│   │   │   │   ├───Potion
│   │   │   │   └───Weapon & Tool
│   │   │   └───Trees
│   │   │       ├───Tree 1
│   │   │       ├───Tree 10
│   │   │       ├───Tree 11
│   │   │       ├───Tree 12
│   │   │       ├───Tree 13
│   │   │       ├───Tree 14
│   │   │       ├───Tree 15
│   │   │       ├───Tree 2
│   │   │       ├───Tree 3
│   │   │       ├───Tree 4
│   │   │       ├───Tree 5
│   │   │       ├───Tree 6
│   │   │       ├───Tree 7
│   │   │       ├───Tree 8
│   │   │       └───Tree 9
│   │   ├───Sprites
│   │   │   └───Cats
│   │   │       ├───Cat-1
│   │   │       ├───Cat-2
│   │   │       ├───Cat-3
│   │   │       ├───Cat-4
│   │   │       ├───Cat-5
│   │   │       ├───Cat-6
│   │   │       └───Meow-VFX
│   │   ├───Textures
│   │   └───UI
│   ├───Logos
│   │   ├───Fonts
│   │   ├───Galaxaris
│   │   │   ├───AI
│   │   │   └───Inspis
│   │   └───Omicronde
│   ├───OST
│   ├───Photos-de-pieds
│   └───SFX
├───editor
│   ├───assets
│   │   ├───Fonts
│   │   └───icons
│   ├───tk_utils
├───game
│   ├───assets
│   │   ├───Fonts
│   │   ├───Images
│   │   │   ├───Background
│   │   │   │   ├───Parallax
│   │   │   │   │   └───Forest
│   │   │   │   └───Tiles
│   │   │   ├───Player
│   │   │   │   ├───little robot
│   │   │   │   ├───MaskDude
│   │   │   │   └───NinjaFrog
│   │   │   ├───Terrain
│   │   │   └───UI
│   │   ├───Music
│   │   └───SFX
│   ├───audio_manager
│   ├───game_actions
├───Tuto API
└───_Omicronde
```

-----------

## Detailed project tree

```
Galaxaris
│   25-26-EFREI_PITI250_Guide de CDC.docx
│   25-26-EFREI_PITI250_Trame de CdC.docx
│   galaxaris.code-workspace
│   Omicronde.zip
│
├───.github
│   └───profile
│           README.md
|           PROJECT_TREE.md
│
├───.share
│   │   icon.ico
│   │   icon.png.png
│   │   LICENSE
│   │   logogalaxaris.jpeg
│   │   README.md
│   │   splash without background.png
│   │   splash.jpg
│   │   splash_newgen.png
│   │
│   └───tests-pygame-GauGoth
│       ├───platformer
│       │   │   main.py
│       │   │
│       │   └───src
│       │       │   README.md
│       │       │   tutorial.py
│       │       │
│       │       └───assets
│       │
│       ├───rain_dodge
│       │       background_etoiles.jpg
│       │       main.py
│
├───api
│   │   .gitignore
│   │   Game.py
│   │   GameObject.py
│   │   LICENSE.md
│   │   README.md
│   │   TODO.md
│   │   __init__.py
│   │
│   ├───assets
│   │   │   Animation.py
│   │   │   AudioManager.py
│   │   │   Resource.py
│   │   │   Texture.py
│   │   │
│   │
│   ├───engine
│   │   │   GameCamera.py
│   │   │   Scene.py
│   │   │
│   │
│   ├───entity
│   │   │   Entity.py
│   │   │   Player.py
│   │   │   Projectile.py
│   │   │   __init__.py
│   │   │
│   │
│   ├───environment
│   │   │   Background.py
│   │   │   Parallax.py
│   │   │   Solid.py
│   │   │   Trigger.py
│   │   │
│   │
│   ├───items
│   │   │   ActiveItem.py
│   │   │   Catalog.py
│   │   │   Inventory.py
│   │   │   Item.py
│   │   │
│   │
│   ├───physics
│   │   │   Collision.py
│   │   │   Time.py
│   │   │   Trajectory.py
│   │   │   __init__.py
│   │   │
│   │
│   ├───UI
│   │   │   Button.py
│   │   │   Dialog.py
│   │   │   GameUI.py
│   │   │   Image.py
│   │   │   Modal.py
│   │   │   Text.py
│   │   │   TextBox.py
│   │   │
│   │
│   ├───utils
│   │   │   Console.py
│   │   │   Constants.py
│   │   │   Debug.py
│   │   │   DebugElement.py
│   │   │   Fonts.py
│   │   │   GlobalVariables.py
│   │   │   Inputs.py
│   │   │   ResourcePath.py
│   │   │   State.py
│   │   │
│   │
│
├───art-department
│   │   .gitignore
│   │   LICENSE
│   │   README.md
│   │
│   ├───Graphisms
│   │   ├───Backgrounds
│   │   │   │   .gitignore
│   │   │   │   clouds.png
│   │   │   │   far-grounds.png
│   │   │   │   sea.png
│   │   │   │   sky.png
│   │   │   │
│   │   │   ├───Pixel-Art Background 1
│   │   │   ├───Pixel-Art Background 2
│   │   │   ├───Pixel-Art Background 3
│   │   │   └───Pixel-Art Background 4
│   │   ├───Items
│   │   ├───Sprites
│   │   ├───Textures
│   │   └───UI
│   ├───Logos
│   │   │
│   │   ├───Fonts
│   │   ├───Galaxaris
│   │   └───Omicronde
│   │
│   ├───OST
│   │
│   ├───Photos-de-pieds
│   │
│   └───SFX
│           blblblbl.mp3
│           Bruit tir golf.mp3
│           Campfire.mp3
│           Casserole 6 - full.mp3
│           Casserole.mp3
│           DSI-Alarm.mp3
│           frog-sound.mp3
│           Full money.mp3
│           LEGO R2D2 death.mp3
│           metal pipe falling sound effect.mp3
│           Pièce qui tombe.mp3
│           PorteKiGrince.mp3
│           r2-hover.mp3
│           r2-navclose.mp3
│           r2-navopen.mp3
│           r2-zoomin.mp3
│           r2-zoomout.mp3
│           Son mer.wav
│           TIE fighter sound loop.mp3
│           Windy-Snow-Storm-Blizzard.mp3
│
├───editor
│   │   .gitignore
│   │   main.py
│   │   PgApp.py
│   │   ReadApiGa.py
│   │   RUNME.bat
│   │   __init__.py
│   │
│   ├───assets
│   │   │   grid.png
│   │   │
│   │   ├───Fonts
│   │   │       Gm6x11.ttf
│   │   │       m6x11.ttf
│   │   │       m6x11plus.ttf
│   │   │
│   │   └───icons
│   │           pause.png
│   │           play.png
│   │           replay.png
│   │
│   ├───tk_utils
│   │   │   ButtonsFunctions.py
│   │   │   KeyRedirection.py
│   │   │   MenuBarGeneration.py
│   │   │   TtkCss.py
│   │   │   UIGeneration.py
|
├───game
│   │   .gitignore
│   │   LICENSE.md
│   │   main.py
│   │   README.md
│   │   RUNME.bat
│   │   __init__.py
│   │
│   ├───assets
│   │   │   credits.txt
│   │   │
│   │   ├───Fonts
│   │   │       Gm6x11.ttf
│   │   │       m6x11.ttf
│   │   │       m6x11plus.ttf
│   │   │
│   │   ├───Images
│   │   │   │   icon.png
│   │   │   │   sign.png
│   │   │   │
│   │   │   ├───Background
│   │   │   │   ├───Parallax
│   │   │   │   │   └───Forest
│   │   │   │   │           0.25x parallax-demon-woods-bg.png
│   │   │   │   │           0.5x parallax-demon-woods-far-trees.png
│   │   │   │   │           0.70x parallax-demon-woods-mid-trees.png
│   │   │   │   │           0.9x parallax-demon-woods-close-trees.png
│   │   │   │   │
│   │   │   │   └───Tiles
│   │   │   │           Blue.png
│   │   │   │           ggg.png
│   │   │   │
│   │   │   ├───Player
│   │   │   │   ├───little robot
│   │   │   │   │       idle_robot.png
│   │   │   │   │       robot_sprite.png
│   │   │   │   │       robot_sprite_sheet.png
│   │   │   │   │
│   │   │   │   ├───MaskDude
│   │   │   │   │       double_jump.png
│   │   │   │   │       fall.png
│   │   │   │   │       hit.png
│   │   │   │   │       idle.png
│   │   │   │   │       jump.png
│   │   │   │   │       run.png
│   │   │   │   │       wall_jump.png
│   │   │   │   │
│   │   │   │   └───NinjaFrog
│   │   │   │           fall.png
│   │   │   │           hit.png
│   │   │   │           idle.png
│   │   │   │           jump.png
│   │   │   │           run.png
│   │   │   │
│   │   │   ├───Terrain
│   │   │   │       beach_sand.png
│   │   │   │       grass.png
│   │   │   │
│   │   │   └───UI
│   │   ├───Music
│   │   │       Alicia.mp3
│   │   │       Cry Of The Celts (Single Edit With Taps).mp3
│   │   │       Gestral Beach - My Grandma Hits Harder!.mp3
│   │   │
│   │   └───SFX
│   │           blblblbl.mp3
│   │           Bruit tir golf-GameOver.mp3
│   │           Bruit tir golf.mp3
│   │           Casserole.mp3
│   │           frog-sound.mp3
│   │           LEGO R2D2 death.mp3
│   │           r2-navclose.mp3
│   │
│   ├───audio_manager
│   ├───game_actions
│   │   │   combat.py
│   │   │   level.py
│   │   │   triggers.py
│   │   │   ui.py
│   │   │
│
├───Tuto API
│       New Section 1.one
│       Open Notebook.onetoc2
│
└───_Omicronde
    │   Omicronde.exe
    │
    └───_internal
        ├───assets
        │   ├───Fonts
        │   │       Gm6x11.ttf
        │   │       m6x11.ttf
        │   │       m6x11plus.ttf
        │   │
        │   ├───Images
        │   │   │   grass.png
        │   │   │   icon.png
        │   │   │
        │   │   ├───Background
        │   │   │   ├───Parallax
        │   │   │   │   └───Forest
        │   │   │   │           0.25x parallax-demon-woods-bg.png
        │   │   │   │           0.5x parallax-demon-woods-far-trees.png
        │   │   │   │           0.70x parallax-demon-woods-mid-trees.png
        │   │   │   │           0.9x parallax-demon-woods-close-trees.png
        │   │   │   │
        │   │   │   └───Tiles
        │   │   │           Blue.png
        │   │   │           ggg.png
        │   │   │
        │   │   └───Player
        │   │       ├───little robot
        │   │       │       robot_sprite.png
        │   │       │       robot_sprite_sheet.png
        │   │       │
        │   │       └───NinjaFrog
        │   │               fall.png
        │   │               hit.png
        │   │               idle.png
        │   │               jump.png
        │   │               run.png
        │   │
        │   ├───Music
        │   │       Alicia.mp3
        │   │       Cry Of The Celts (Single Edit With Taps).mp3
        │   │       Gestral Beach - My Grandma Hits Harder!.mp3
        │   │
        │   └───SFX
        │           blblblbl.mp3
        │           Bruit tir golf-GameOver.mp3
        │           Bruit tir golf.mp3
        │           Casserole.mp3
        │           frog-sound.mp3
        │           r2-navclose.mp3
```