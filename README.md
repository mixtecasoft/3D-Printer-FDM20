# 3D-Printer-FDM20 

> FDM20 3D printer configuration

---

## Tabla de contenido

- [Configuration](#Configuration)
- [GUI](#GUI)
- [Slicer](#Slicer)
- [Licencia](#License )


---

## Configuration 

After installing the software, the first thing to do is to configure the
printer in both Repetier Host and Slic3r.

Below are the steps to follow for the configuration in both softwares:

### Repetier Host

In Repetier Host select from the **Config -> Printer Settings** 

![Printer Settings](https://user-images.githubusercontent.com/60562869/74582688-97d7c880-4f84-11ea-87cc-05907591a82e.gif)


The following menu will be displayed with different options. It is necessary to have the same settings shown in the following images.


| Connection | Printer |  Extruder   |  Printer Shape  |
| :---: |:---:| :---:| :---:|
|  ![Connection](https://user-images.githubusercontent.com/60562869/74582800-1719cc00-4f86-11ea-84fd-95daee027410.PNG) | ![Printer](https://user-images.githubusercontent.com/60562869/74582816-3a447b80-4f86-11ea-9b07-e89c3e7f9503.PNG)  | ![Extruder](https://user-images.githubusercontent.com/60562869/74582818-3d3f6c00-4f86-11ea-928d-f5ef1316307e.PNG) |  ![Printer Shape](https://user-images.githubusercontent.com/60562869/74582819-429cb680-4f86-11ea-8969-8e4398db36be.PNG) |
| The communication port depends on the operating system. |   |  |   |

When making all the changes it is necessary to press the Apply button at the bottom of the box and then click on the OK button.

### Slic3r

Now it is necessary to configure Slic3r for the correct processing of the models to be printed. For
this is necessary to go to the Slic3r tab on the right side of the Software, just below the **Printer
Settings** used for the Repetier Host configuration.

In this tab it is necessary to select the option **Slic3r** in Slicer. Subsequently it should beopen the **Slic3r** configuration by pressing the **Configuration** button. 

<img src="https://user-images.githubusercontent.com/60562869/74582977-13874480-4f88-11ea-9921-3141187a6b94.gif" width="400" height="450" />


Doing this will open a new configuration window for the Slic3r processing software. In this window, we must go to the menu **File -> Load Config Bundle** and we must select the **FDM20.ini** configuration file that appears in this repository.

![Load Config](https://user-images.githubusercontent.com/60562869/74583023-7ed11680-4f88-11ea-8a6f-e97a1fb2b059.PNG)

We must save all loaded configurations to be able to use them correctly.

![Save ini](https://user-images.githubusercontent.com/60562869/74584185-15a3d000-4f95-11ea-8b97-37c27eb597bf.gif)

## GUI
### Graphic interface

When the program is initialized, a window divided into 3 main environments opens:
1. 3D environment navigation
1. 3D model options
1. Log

![Final](https://user-images.githubusercontent.com/60562869/74583590-2a309a00-4f8e-11ea-8b12-a93a2ff951d8.PNG)

### 3D environment navigation

1. Rotate
1. Move View
1. Zoom
1. Frame objects
1. Isometric view
1. Front view
1. Top view
1. Parallel Projection

![Navigation](https://user-images.githubusercontent.com/60562869/74583323-8940df80-4f8b-11ea-9c35-c8dd846dbad4.PNG)


### 3D model options

To add the model, you have the option Drag and Drop, or else you must press the button with the add symbol.

![Options 3D](https://user-images.githubusercontent.com/60562869/74583361-f6547500-4f8b-11ea-8e9b-a03c65015fd6.PNG)

When you open a model, a new group of objects will appear with the model as a list. It is possible to add several models at the same time. In addition, in the navigation section of the 3D environment, the added model or models will be displayed.

### Slicer

After loading a model it is necessary to switch to the Slicer tab and verify that the FDM20 printer settings are selected.
Once the settings have been made, press the Slice with slic3r button.

<img src="https://user-images.githubusercontent.com/60562869/74583660-da060780-4f8e-11ea-8031-20c7f42d4422.png" width="380" height="450" />

### Print Preview

1. In automatic, the program will begin with the processing of the model and at the end it will change to the Print Preview tab. In this tab there are 4 buttons in the upper part and in the lower one it shows information about approximate printing times, amount of material to be used, in addition to allowing the visualization of the routes to be followed by the printer and / or the layers that will make up the printed model.

2. The buttons allow printing to start if the printer is connected to the computer (Print), edit the g code that will be sent to the printer (Edit G-Code) and save the file (Save to File / Save for SD Print).

3. When you press Save for SD Print, the start and end code G is added automatically set to Repetier.

4. The Save to File button only saves it for the purpose of open it again and send to print from the computer. Once the file is saved, it is copied to the SD memory, and sent directly to the printer.

<img src="https://user-images.githubusercontent.com/60562869/74583664-edb16e00-4f8e-11ea-9d4d-374ebba75d9b.PNG" width="380" height="450" />


###  Log

This tab shows the commands and actions that Repetier executes.

![Console](https://user-images.githubusercontent.com/60562869/74583448-cf4a7300-4f8c-11ea-9031-931a97e63e33.PNG)

---
### Additional features
1. If you want to know more about the operation of Repetier Host and / or any of its options, go to the  [Repetier-Host](http://www.repetier.com/tutorials/) tutorials page.

2. To view the full video of the FDM 20 3D printer setup, go to the following [YouTube](https://www.youtube.com/watch?v=67wcuKeKQ7k&t=306s) or [GitHub](https://github.com/ProyectilMx) links created by Projectile Mx.


## License  

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
- Copyright 2015 © <a href="http://fvcproductions.com" target="_blank">FVCproductions</a>.

***Created by Mixtecasoft, designed to learn.***
