
![screenshot](https://ipvxhq.bn.files.1drv.com/y4m-nWQqS0jyDAPReZyHZSWZsqEyqOdsHPXeNfN01DKtB3FtaoGu2g4nDTjxLWyv0q8g0sZbec_iUI-C7YO8aFuK-qMWUneYMdTx0CZcwX-cFTaSkxon9a40oLIRj0lO_LEkN8EhcIVcjrZyWy7sa6baOThII5xh4K2PnpjildyRLqJhavjjQ9BCXWzTeIkHUzeuroigN4fkqdR53ts3UzZEg/Video_1521591797.gif?psid=1)

# Godot CHIP-8 Emulator

A CHIP-8 emulator made with Godot (version 3.0.2 stable).

This is a port to GDScript of a CHIP-8 emulator written originally in Java.

The original Java emulator was created by [Johan](https://github.com/Johnnei/) based on his [YouTube](https://www.youtube.com/playlist?list=PL5PyurErl12czoLyYD8za68d61T_OZsP2) tutorials.

## Binaries

Binaries for the most up to date versions:

* [Linux](https://1drv.ms/u/s!Ao1E4OCcZiFLjeQq2-4osd-VkElvDQ): Linux binary
* [Windows](https://1drv.ms/u/s!Ao1E4OCcZiFLjeQn--HUDudbb0uB4A): Windows binary
* [Mac OSX](https://1drv.ms/u/s!Ao1E4OCcZiFLjeQpMVwghBxa93sZ3w): Mac OSX binary


Old binaries for 2.x versions are still available:

* [Linux](https://1drv.ms/u/s!Ao1E4OCcZiFLjbMFKweFLqk-9yLpfQ): Linux binary
* [Windows](https://1drv.ms/u/s!Ao1E4OCcZiFLjbMGziMPz4i-YY2KSQ): Windows binary
* [Mac OSX](https://1drv.ms/u/s!Ao1E4OCcZiFLjbMEEnr2vz1lBNwGaQ): Mac OSX binary

## Getting Started

To run the project inside Godot load the `res://main.tscn` scene.

## Controlling the games

The original CHIP-8 uses 16 keys mapped to the following layout:

 ``1 2 3 C``
 
 ``4 5 6 D``
 
 ``7 8 9 E``
 
 ``A 0 B F``

The current implementation maps these keys to its correspondents in the keyboard: 1-9 and A-F.


## Built With

* [Godot](https://godotengine.org/) - Godot is an advanced, feature-packed, multi-platform 2D and 3D open source game engine
* [CRT Shader](https://github.com/henriquelalves/SimpleGodotCRTShader) - A simple Godot shader that simulates CRT Displays
* [Java CHIP-8 Emulator](https://github.com/Johnnei/Youtube-Tutorials/tree/master/emulator_chip8) - Original CHIP-8 Emulator Java code developed by Johan 


## Authors

* **Johan** - *Original Java code* - [CHIP-8 Java](https://github.com/Johnnei/Youtube-Tutorials/tree/master/emulator_chip8)
* **Vitor Almeida da Silva** - *Port to Godot* - [Godot CHIP-8 Emulator](https://github.com/vitoralmeidasilva)


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
