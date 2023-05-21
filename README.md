macos

Macos OS (Flutter)

███╗ ███╗ █████╗ ██████╗ ██████╗ ███████╗
████╗ ████║██╔══██╗██╔════╝██╔═══██╗██╔════╝
██╔████╔██║███████║██║ ██║ ██║███████╗
██║╚██╔╝██║██╔══██║██║ ██║ ██║╚════██║
██║ ╚═╝ ██║██║ ██║╚██████╗╚██████╔╝███████║
╚═╝ ╚═╝╚═╝ ╚═╝ ╚═════╝ ╚═════╝ ╚══════╝

---

## **Temario full guide**

- [**Rosseta Software**](1)
- [**Xcode**](#Xcode)
- [**Homebrew**](#Homebrew)
- [**Ruby**](#Ruby)
  - [**Utilidades & requerimientos**](#table-of-contents)
    - [**Git**](#Git)
    - [**Cocopods**](#Cocopods)
    - [**Watchman**](#Watchman)
    - [**pod**](#pod)
    - [**fifi**](#fifi)
    - [**Podman**](#Podman)
- [**Flutter**](#Flutter)
  - **Config & Setup**
- [**VS Code**](#VS-Code)
  - [**Extensiones**](#table-of-contents)
  - [**Config & Setup**](#table-of-contents)
- [**Android Studio**](#Android-Studio)
  - [**Config & Flutter Setup**](#Config-&-Flutter-Setup)

---

## **[Rosseta-Software](1)**

```bash

softwareupdate --install-rosetta

```


```bash

sudo softwareupdate --install-rosetta --agree-to-license

```


--------------------------------------
<div id='2' />
# Xcode



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
