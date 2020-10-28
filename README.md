# SFML_Space-Shooter-Game

A simple 2d space shooter game created by C++ and SFML(Simple and Fast Multimedia Library) with CLion IDE.

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

## Table of Contents

- [Background](#Background)
- [Exhibition](#Exhibition)
- [Install](#install)
- [Ideas](#Ideas)
- [Structure](#Structure)
- [Maintainers](#Maintainers)
- [License](#license)

## Background

3D render engines that are nowdays used in games. I write a very simple 3d render engine demo so that it will really help me understand some fundamental principles which are also used for modern render engines.

Through making this render engine, I learn about orthographic projection, simple triangle rasterization, z-buffering, flat shading and subdividing a tetrahedron to a sphere.

## Exhibition

Needs to be updated...

## Install

I Use C++ language, [SFML(Simple and Fast Multimedia Library)](https://www.sfml-dev.org/index.php) and CLion (an IDE) under Windows 10 environment for this project.

[CLion Download](https://www.jetbrains.com/clion/download/#section=windows)<br>

## Ideas

1. Complete main game loop by processing each event and real time input while window is open and set time fixed for each frame using sf::Clock and sf::Time class provided by SFML.

2. Use C++ template and inline files to build resource holder for each type of resource(Textures, Fonts and so on).

3. Use multiple inheritance to build the game world. SceneNode class as a virtual base class which controls the whole game world and each layer's entrance(for instance, background layer, air layer and son on). SpriteNode class is a derived class which inherits SceneNode class and take control of background settings. Entity class is a intermediate class which inherits SceneNode class and represents each entity in the game. Aircraft class is a derived class which inherits Entity class and take control of all aircraft objects' behaviour.

4. Use Command pattern to handle each user event or real time input as a command, push each command into the command queue and execute and pop each front command one by one. 

## Structure

(Here should be an UML model to display the structure of the program).

The whole project contains four main folders, **Screenshots and GIFs** folder, **Media** folder, **include** folder and **src** folder.

**Screenshots and GIFs** folder contains all screenshots and GIFs needed for exhibition.

**src** folder contains altogether **10** `C++` source files:

Needs to be updated...

**include** folder contains altogether **15** `C++` header files:

Needs to be updated...

**Media** folder contains all **media** files(fonts, pictures, textures).

## Maintainers

[@Yunxiang-Li](https://github.com/Yunxiang-Li).

## License

[MIT license](https://github.com/Yunxiang-Li/SFML_Space-Shooter-Game/blob/main/LICENSE)
