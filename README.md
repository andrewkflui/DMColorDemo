# Interactive Demo of Colors in Digital Multimedia 

A set of Java applications each of which an interactive demonstration application about colors in digital multimedias.

Developed in 2009 to 2010

Copyright (C) 2010 - Andrew Kwok-Fai Lui

The Open University of Hong Kong

This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program; if not, see http://www.gnu.org/licenses/.

## Introduction

There are 5 interactive demo applications included in this package

1. Color RGB Space Demo (`faifai.color.ColorSpaceDemo`)
2. Color HSB Space Demo (`faifai.color.ColorSpaceHSBDemo`)
3. White Plane Reflection Demo (`faifai.color.ColorReflectionDemo2D`)
4. Color Plane Reflection Demo (`faifai.color.ColorPlaneReflectionDemo2D`)
5. Mix Light Reflection Demo (`faifai.color.ColorMixLightDemo2D`)

## Running the Applications

### Pre-requisites

1. Java JRE 1.8 or above

### Running the Applications Through the Launcher

A launcher application `ApplicationLauncher.class` is provided for running each of the 5 applications.

1. Download the repository to a folder, assuming that it is `/app/DMColorDemo`. The Java classes are found in the `bin` folder.
2. Execute `ApplicationLauncher.class` insider the folder

> `cd /app/DMColorDemo`
> 
> `java -cp "./bin" ApplicationLauncher`

### Running Individual Application

Alternatively, each of the 5 applications can be executed from their main classes (as in the above list).

> `cd /app/DMAudioDemo`
> 
> `java -cp "./bin" faifai.color.ColorMixLightDemo2D`

## Overview of the Applications

### Color RGB Space Demo 
Class: `faifai.color.ColorSpaceDemo`
* Interactive color viewing of RGB values
* Named colors and their RGB values

<img width="592" alt="Screenshot 2022-10-31 at 1 50 18 AM" src="https://user-images.githubusercontent.com/8808539/198893750-052be0a3-2cb9-4dfa-9656-a8e22f260dc5.png">

### Color HSB Space Demo 
Class: `faifai.color.ColorSpaceHSBDemo`
* Interactive color viewing of HSB and RGB values
* Named colors and their HSB values
<img width="652" alt="Screenshot 2022-10-31 at 1 50 37 AM" src="https://user-images.githubusercontent.com/8808539/198893788-a617129c-6035-471a-af97-8d9cebfa2ba6.png">

### White Plane Reflection Demo 
Class: `faifai.color.ColorReflectionDemo2D`)
* Light shining on a white plane (perfect reflector)
* Interactive adjust the color of the light source
<img width="822" alt="Screenshot 2022-10-31 at 1 50 50 AM" src="https://user-images.githubusercontent.com/8808539/198893847-454f6b0b-e5b0-4f62-bf08-c80a094918cb.png">

### Color Plane Reflection Demo 
Class: `faifai.color.ColorPlaneReflectionDemo2D`)
* Light shining on a plane of different colors
* Interactive adjust the color of the light source and the color of the reflecting plane
<img width="822" alt="Screenshot 2022-10-31 at 1 51 07 AM" src="https://user-images.githubusercontent.com/8808539/198893909-497363f9-d42b-4a16-af94-3162014a8a53.png">

### Mix Light Reflection Demo 
Class: `faifai.color.ColorMixLightDemo2D`
* Two light sources shining on a white plane (perfect reflector), mixing of two colors.
* Interactive adjust the colors of the two light source
<img width="822" alt="Screenshot 2022-10-31 at 1 51 18 AM" src="https://user-images.githubusercontent.com/8808539/198893974-d9c7e35f-041d-4cf8-af04-bf468974291d.png">





