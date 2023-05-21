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

- [**Rosseta Software**](#id1)
- [**Xcode**](#id2)
- [**Homebrew**](#id3)
- [**Ruby**](#id4)
  - [**Utilidades & requerimientos**](#id4.1)
    - [**Git**](#id4.2)
    - [**Cocopods**](#id4.3)
    - [**Watchman**](#id4.4)
    - [**pod**](#id4.4)
    - [**fifi**](#id4.5)
    - [**Podman**](#id4.6)
- [**Flutter**](#id5)
  - [**Config & Setup**](#id5.2)
- [**VS Code**](#id6)
  - [**Extensiones**](#id6.1)
  - [**Config & Setup**](#id6.2)
- [**Android Studio**](#id7)
  - [**Config & Flutter Setup**](id#7.1)

------------------




<div id='1' />
1.  Rosseta-Software

```bash

softwareupdate --install-rosetta

```


```bash

sudo softwareupdate --install-rosetta --agree-to-license

```


--------------------------------------
<div id='2' />
## Xcode



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
