---
layout: post
title:  "Introduction to UDrive"
description: "FOSS Vehicle simulation library for Unity"
date:   2022-04-04 20:15:00 +0200
categories: udrive
thumbnail: /assets/udrive/udrive0.1thumb.jpg
---
![UDrive thumbnail](/assets/udrive/udrive0.1thumb.jpg)
If you want to add a physics based car to your unity game you have quite a few different options:

* WheelCollider
    * Included with Unity
    * No source available
    * Wheel suspension and collision only - you have to do the rest yourself
    * Raycast collision
    * Questionable accuracy, very hard to tune
* Edy's vehicle physics
    * Available from Asset Store ($60) (demo available)
    * Source included
    * Everything included for a functional vehicle
    * Suspension uses WheelCollider internally
* NWH Vehicle Physics 2
    * Available from Asset Store ($74)
    * Source included
    * Everything needed for a working vehicle included
    * Custom 3D wheel collision
    * Networking support for Photon and Mirror (lol)

So if you want actually usable vehicle simulation system you have to pay for it, UDrive package aims to provide most of the features of these proprietary systems for free.

### Planned features
* Support for various wheeled vehicles (cars, motorcycles, trucks)
* Custom wheel collision (mostly working)
* Custom friction calculation (partially working)
* Full drivetrain simulation - connect the engine to the wheels in arbitrary configurations (mostly working)
* Vehicle state serialization and deserialization - demos and networking support (not implemented)
* Vehicle assists (ABS, TCS, ESC) (partially working)
* InputSystem and InputManager support
* Installs as a modern Unity package (no Assets folder clutter)

Right now the project isn't ready but when i get closer to the final library i will upload the repository on GitHub under LGPL v3.0 license.

<iframe width="560" height="315" src="https://www.youtube.com/embed/uAnEjFwO6aw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>