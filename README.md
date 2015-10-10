# ImoutoProject
Imouto Project is a .Net software solution that helps you store and organize images on your local machine.

## Requirements
1. OS: Windows Vista SP2 and above (7, 8, 8.1, 10)
2. .NET Framework 4.5 (already installed on windows  8 and above, [can be downloaded here](http://www.microsoft.com/ru-ru/download/details.aspx?id=44927))

## [Quick start guide](https://github.com/ImoutoChan/ImoutoProject/wiki/Quick-start-guide)

## [Download last realease](https://github.com/ImoutoChan/ImoutoProject/releases)

## Content
Imouto Project contains 4 parts. You can use some of them independently, but others depend on each other.

### Parts

#### 1. Imouto Viewer
Dependences: none

/screens/

The desktop application for viewing images. 

Features:
* Fixed zoom
* Slideshows
* Easy navigation through complex folder structures
* Convenient zoom presets
* Support tags and notes, that stores in **Imouto Service**

Hotkeys and detailed description of functionality can be found here.

#### 2. Imouto Service
Dependence: Imouto Navigator (for initial configuration)

Background application, that provides information storing and related services.

Features:
* Organize your images collections
* Store images meta information
* Integrity control for your collections
* Provide information for **Imouto Extensions** (described below)
* Parse and store tags information from Booru sites (support Danbooru, Yandere, SankakuComplex)
* Provide tag information for **Imouto Viewer**
* Provide services for **Imouto Navigator**

Installation procedure, initial configuration, and other useful information can be found here.

#### 3. Imouto Navigator
Dependence: Imouto Service

/screens/

The desktop application, that provides you interface for browse your collections and configure **Imouto Service**.

Features:
* Browse your images collections
* Agile search by tags
* Convenient tags add functionality
* Configuration of your collections for **Imouto Service**
* Webm/gif preview

Additional information can be found here.

#### 4. Imouto Extensions
Dependence: Imouto Service

/screens/

Extensions for Chrome and Firefox, that highlights already saved images/relatives of already saved images on popular boorus.

Installation information can be found here.
