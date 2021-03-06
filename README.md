# Pixel Vision 8 v2.0 - DotNet Template

Pixel Vision 8's core philosophy is to teach retro game development with streamlined workflows. This template was designed to help get you up and running as quickly as possible with making your first PV8 game with C#.

## Quick Start Guide

I've tried my best to make compiling, testing, and packaging a new game as easy as possible. While you can learn more about this in the [docs](https://github.com/PixelVision8/PixelVision8/wiki), here is the quickest way to build a game with this template:

> Before you get started, you are going to want to install [.Net 6](https://dotnet.microsoft.com/download/dotnet/6.0). The project itself will need, [NodeJS](https://nodejs.org/en/download/), and an IDE like [Visual Studio Code](https://code.visualstudio.com/Download).

1. Install the dotnet template `> dotnet new --install PixelVision8.Template`
2. Crete a new project `> dotnet new pv8-game --name MyGame`
3. Open the project in `VS Code` or the command line `> cd MyGame`
4. Install the NodeJS dependencies `> npm install`
5. Run the default Gulp action `> gulp`
6. Launch the `.dll` manually `dotnet App/bin/Debug/My\ Game\ 8.dll`

If you want to build executables, you can use the Gulp action `> gulp package`. This will create a new `Releases/Final/` folder, and inside, you'll zip files for Windows, Mac, and Linux.

Finally, you can use Visual Studio Code to debug a build by running one of the custom tasks included in the `.vscode` folder.

## Making A Game

You'll find everything you need to run and package a Pixel Vision 8 game in the `App` folder. Outside of renaming the game, you'll want to add your own project to the `Game` folder or pick one of the pre-existing `code` files to make your own from scratch. By default, PV8 will automatically load the `code.cs` file so you should delete it if you want to make a Lua game. 

## Credits

Pixel Vision 8 was created by Jesse Freeman ([@jessefreeman](http://twitter.com/jessefreeman)) in collaboration with Christina-Antoinette Neofotistou ([@CastPixel](http://twitter.com/CastPixel)) for art, and Christer Kaitila ([@McFunkypants](http://twitter.com/McFunkypants)) for music. 

With additional contributions by the following people:

* Pedro Medeiros
* Shawn Rakowski
* Drake Williams
* Matt Hughson
* Dean Ellis

And special thanks to Jan Rochat, Ethan Shaughnessy, and our other sponsors.

## License

Pixel Vision 8 is Licensed under the [Microsoft Public License (MS-PL) License](https://opensource.org/licenses/MS-PL). See the [LICENSE file](https://github.com/PixelVision8/PixelVision8/blob/master/LICENSE.txt) in the project root for complete license information.

Pixel Vision 8 is Copyright (c) 2017-2021 Jesse Freeman. All rights reserved.