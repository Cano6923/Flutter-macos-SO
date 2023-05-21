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

- [**Rosseta Software**](#Rosseta-Software)
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

## **Rosseta-Software**

```bash
softwareupdate --install-rosetta
```

```bash
sudo softwareupdate --install-rosetta --agree-to-license
```

## **Xcode**

## **Homebrew**

## **Ruby**

- <div id='id4.1' />
  ## Cocopods
  

````
* <div id='id4.1' />
## Pod

```bash
````

- <div id='id4.1' />
  ## Podsman
  

- <div id='id4.1' />
  ## fifi
  

- <div id='id4.1' />
  ## watchman
  

````
* <div id='id4.1' />
## fifi

```bash
````

## **Fluttter**

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

IOS Xcode Setup

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

## **VS-Code**

- <div id='id6.1' />
  ##
  
- <div id='id6.2' />
  ##
  

## **Android-Studio**
