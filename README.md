macos

Macos OS (Flutter)

███╗ ███╗ █████╗ ██████╗ ██████╗ ███████╗
████╗ ████║██╔══██╗██╔════╝██╔═══██╗██╔════╝
██╔████╔██║███████║██║ ██║ ██║███████╗
██║╚██╔╝██║██╔══██║██║ ██║ ██║╚════██║
██║ ╚═╝ ██║██║ ██║╚██████╗╚██████╔╝███████║
╚═╝ ╚═╝╚═╝ ╚═╝ ╚═════╝ ╚═════╝ ╚══════╝

--------------------------------------

## **Temario full guide**

- [**Rosseta Software**](#1)
- [**Xcode**](#2)
- [**Homebrew**](#3)
- [**Ruby**](#4)
  - [**Utilidades & requerimientos**](#4.1)
    - [**Git**](#4.2)
    - [**Cocopods**](#4.3)
    - [**Watchman**](#4.4)
    - [**pod**](#4.4)
    - [**fifi**](#4.5)
    - [**Podman**](#4.6)
- [**Flutter**](#5)
  - [**Config & Setup**](#5.2)
- [**VS Code**](#6)
  - [**Extensiones**](#6.1)
  - [**Config & Setup**](#6.2)
- [**Android Studio**](#7)
  - [**Config & Flutter Setup**](#7.1)

------------------


<div id='1' />
##Rosseta-Software

```bash

softwareupdate --install-rosetta

```


```bash

sudo softwareupdate --install-rosetta --agree-to-license

```


--------------------------------------
<div id='2' />
##Xcode



```bash


```

```bash


```


--------------------------------------
<div id='3' />
## Homebrew


```bash


```

```bash


```

```bash


```


--------------------------------------
<div id='4' />
## Ruby

```bash


```

* <div id='id4.1' />
  ## Cocopods

  ```bash


  ```

* <div id='id4.1' />
  ## Pod

  ```bash


  ```

* <div id='id4.1' />
  ## Podsman


  ```bash


  ```

* <div id='id4.1' />
  ## fifi


  ```bash


  ```
 
* <div id='id4.1' />
  ## watchman

  ```bash


  ```

--------------------------------------
* <div id='id4.1' />
  ## fifi

  ```bash


  ```



--------------------------------------
<div id='id5' />
## Fluttter


< Intel

```bash
https://storage.googleapis.com/flutter_infra_release/releases/stable/macos/flutter_macos_3.10.1-stable.zip

```

< Apple Silicon

```bash

  https://storage.googleapis.com/flutter_infra_release/releases/stable/macos/flutter_macos_arm64_3.10.1-stable.zip
```

```bash
cd ~/development
unzip ~/Downloads/flutter_macos_3.10.1-stable.zip


```





```bash

export PATH="$PATH:`pwd`/flutter/bin"


```



```bash

which flutter

```




```bash

flutter doctor

```





```bash

git clone https://github.com/flutter/flutter.git -b stable

```




```bash

flutter precache

```


IOS Xcode  Setup 


```bash

sudo xcode-select --switch /Applications/Xcode.app/Contents/Developer

```


```bash

sudo xcodebuild -runFirstLaunch

```





```bash

open -a Simulator


```






```bash

sudo gem uninstall ffi && sudo gem install ffi -- --enable-libffi-alloc


```

--------------------------------------
<div id='id6' />
## VS Code 

* <div id='id6.1' />
  ##

* <div id='id6.2' />
  ##


--------------------------------------
<div id='id7' />
## Android-Studio
