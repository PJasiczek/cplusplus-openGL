# OpenGL
> A collection of small C++ / OpenGL (GLUT) programs — Bezier curve rendering, a Sierpinski carpet fractal, and lit, textured, mouse-controlled 3D shapes — built for a Computer Graphics course.

## Table of contents
* [Technologies](#technologies)
* [Setup](#setup)
* [Status](#status)
* Bezier curve
    * [General info](#general-info)
    * [Screenshots](#screenshots)
* Egg shape
    * [General info](#general-info-1)
    * [Screenshots](#screenshots-1)
* Egg casting
    * [General info](#general-info-2)
    * [Screenshots](#screenshots-2)
* Egg lighting
    * [General info](#general-info-3)
    * [Screenshots](#screenshots-3)
* Egg texturing
    * [General info](#general-info-4)
    * [Screenshots](#screenshots-4)
* Egg two sources lighting
    * [General info](#general-info-5)
    * [Screenshots](#screenshots-5)
* Pyramid texturing
    * [General info](#general-info-6)
    * [Screenshots](#screenshots-6)
* Sierpinski carpet
    * [General info](#general-info-7)
    * [Screenshots](#screenshots-7)
* Teapot casting
    * [General info](#general-info-8)
    * [Screenshots](#screenshots-8)
* Teapot lighting
    * [General info](#general-info-9)
    * [Screenshots](#screenshots-9)
* [Contact](#contact)

## Technologies
* C++ with the OpenGL graphics library and the GL Utility Toolkit extension (GLUT).

## Setup
Programs in this repository require the GLUT (OpenGL Utility Toolkit) library. If it's not already in your development environment, install it as follows:
* Download and unpack the library files: [glut-3.7](./library/glut_3_7.zip)
* Locate the folder containing `gl.h` and place `glut.h` there
* Locate the folder containing `opengl32.lib` and place `glut32.lib` there
* Locate the folder containing `opengl32.dll` and place `glut32.dll` there

## Status
**Archived** — not actively maintained.

Written between late 2018 and early 2019 for a Computer Graphics lab course (Wrocław University of Science and Technology). All ten programs below are complete, as submitted for grading.

# Bezier Curve
## General info
Draws a grid of control points as small connected balls; pressing _W_ shows an approximation of the Bezier surface through them. [Built for the Computer Graphics lab course — task description](http://www.zsk.ict.pwr.wroc.pl/zsk/repository/dydaktyka/gk/zadania_domowe/zadania_3.pdf).

## Screenshots
![Example screenshot](./img/screenshot1.png)
![Example screenshot](./img/screenshot.png)

# Egg shape
## General info
Renders a spinning egg with three switchable models:
* Key _P_ – a model built from _N_ points
* Key _W_ – a wireframe grid formed from those points
* Key _W_ – a model built from randomly filled triangles

[Built for the Computer Graphics lab course — task description](http://www.zsk.ict.pwr.wroc.pl/zsk/dyd/intinz/gk/lab/cw_3_dz/).

## Screenshots
![Example screenshot](./img/screenshot2.png)

# Egg casting
## General info
Renders an egg shape with mouse-driven rotation.
* Left mouse button + horizontal drag – rotate around the y axis
* Left mouse button + vertical drag – rotate around the x axis
* Right mouse button + vertical drag – move the viewpoint closer to the object

[Built for the Computer Graphics lab course — task description](http://www.zsk.ict.pwr.wroc.pl/zsk/dyd/intinz/gk/lab/cw_4_dz/).

## Screenshots
![Example screenshot](./img/screenshot3.png)

# Egg lighting
## General info
Renders a spinning egg illuminated with yellow light. [Built for the Computer Graphics lab course — task description](http://www.zsk.ict.pwr.wroc.pl/zsk/dyd/intinz/gk/lab/cw_5_dz/).

## Screenshots
![Example screenshot](./img/screenshot4.png)

# Egg texturing
## General info
Renders a textured egg with mouse-driven rotation.
* Left mouse button + horizontal drag – rotate around the y axis
* Left mouse button + vertical drag – rotate around the x axis
* Right mouse button + vertical drag – move the viewpoint closer to the object

[Built for the Computer Graphics lab course — task description](http://www.zsk.ict.pwr.wroc.pl/zsk/dyd/intinz/gk/lab/cw_6_dz/).

## Screenshots
![Example screenshot](./img/screenshot5.png)

# Egg two sources lighting
## General info
Renders an egg illuminated by two separate light sources, with the same mouse-driven rotation and zoom as the other egg programs. [Built for the Computer Graphics lab course — task description](http://www.zsk.ict.pwr.wroc.pl/zsk/dyd/intinz/gk/lab/cw_5_dz/).

## Screenshots
![Example screenshot](./img/screenshot10.png)

# Pyramid texturing
## General info
Renders a textured pyramid with mouse-driven rotation and per-face texture toggles.
* Left mouse button + horizontal drag – rotate around the y axis
* Left mouse button + vertical drag – rotate around the x axis
* Right mouse button + vertical drag – move the viewpoint closer to the object
* Keys _P_, _O_, _I_, _U_ – toggle texturing on individual faces of the pyramid
* Key _Y_ – switch between texturing one or two sides
* Key _T_ – toggle texturing of the pyramid surface

[Built for the Computer Graphics lab course — task description](http://www.zsk.ict.pwr.wroc.pl/zsk/dyd/intinz/gk/lab/cw_6_dz/).

## Screenshots
![Example screenshot](./img/screenshot6.png)

# Sierpinski carpet
## General info
[Renders the Sierpinski carpet fractal. Built for the Computer Graphics lab course — task description](http://www.zsk.ict.pwr.wroc.pl/zsk/dyd/intinz/gk/lab/cw_2_dz/).

## Screenshots
![Example screenshot](./img/screenshot7.png)

# Teapot casting
## General info
Renders a wireframe teapot with mouse-driven rotation.
* Left mouse button + horizontal drag – rotate around the y axis
* Left mouse button + vertical drag – rotate around the x axis
* Right mouse button + vertical drag – move the viewpoint closer to the object

[Built for the Computer Graphics lab course — task description](http://www.zsk.ict.pwr.wroc.pl/zsk/dyd/intinz/gk/lab/cw_4_dz/).

## Screenshots
![Example screenshot](./img/screenshot8.png)

# Teapot lighting
## General info
Renders a solid teapot illuminated with white light, with the same mouse-driven rotation and zoom as the other programs. [Built for the Computer Graphics lab course — task description](http://www.zsk.ict.pwr.wroc.pl/zsk/dyd/intinz/gk/lab/cw_5_dz/).

## Screenshots
![Example screenshot](./img/screenshot9.png)
