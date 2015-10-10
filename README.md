# Imouto Project
Imouto Project is a .Net software solution that helps you store and organize images on your local machine.

## Requirements
1. OS: Windows Vista SP2 and above (7, 8, 8.1, 10)
2. .NET Framework 4.5 (already installed on windows  8 and above, [can be downloaded here](http://www.microsoft.com/ru-ru/download/details.aspx?id=44927))

## [Quick start guide](https://github.com/ImoutoChan/ImoutoProject/wiki/Quick-start-guide)

## [Download last release](https://github.com/ImoutoChan/ImoutoProject/releases)

## Content
Imouto Project contains 4 applications. You can use some of them independently, but some depend on others.

### Parts

#### 1. Imouto Viewer
Dependences: none

![Screen](https://dl.dropbox.com/s/6vygurlfirce8rl/2015-10-10_22-10-55.png)

The desktop application for viewing images. 

Features:
* Fixed zoom
* Slideshow
* Easy navigation through complex folder structures
* Convenient zoom presets
* Support tags and notes, that stores in **Imouto Service**

[Hotkeys and detailed description  can be found here.](https://github.com/ImoutoChan/ImoutoProject/wiki/Imouto-Viewer)

#### 2. Imouto Service
Dependence: Imouto Navigator (for initial configuration)

Background application that provides image storing and related services.

Features:
* Organization of your images collections
* Storage of images meta information
* Integrity control for your collections
* Provide information for **Imouto Extensions** (described below)
* Parse and store tags information from Booru sites (support Danbooru, Yandere, SankakuComplex)
* Provide tag information for **Imouto Viewer**
* Provide services for **Imouto Navigator**

[Installation procedure, initial configuration, and other useful information can be found here.](https://github.com/ImoutoChan/ImoutoProject/wiki/Imouto-Service)

#### 3. Imouto Navigator
Dependence: Imouto Service

![Screen](https://dl.dropbox.com/s/qq78he1iubcowm7/2015-10-10_22-18-41.png?dl=0)

The desktop application that provides you interface for browsing your collections and configure **Imouto Service**.

Features:
* Browse your images collections
* Agile search by tags
* Convenient tags adding functionality
* Configuration of your collections for **Imouto Service**
* Webm/gif preview

[Additional information and features description can be found here.](https://github.com/ImoutoChan/ImoutoProject/wiki/Imouto-Navigator)

#### 4. Imouto Extensions
Dependence: Imouto Service

![Screen](https://dl.dropbox.com/s/elf3rkcfkf4esxx/2015-10-10_21-28-43.png?dl=0)

Extensions for Chrome and Firefox that highlights already saved images/relatives of already saved images on popular booru sites like sankakuchannel, danbooru, yandere.

[Installation information can be found here.](https://github.com/ImoutoChan/ImoutoProject/wiki/Imouto-Extensions)
