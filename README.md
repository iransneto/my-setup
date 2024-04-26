# My setup
Divided into apps and shortcuts

# Shortcuts
some helpful shortcuts

this one allow me to open an app directly from terminal
```
$ alias 'open -a <app-name>'
```

# APPS for development
## Home brew
Home brew is a powerfull package manager that we use to install apps by terminal [https://brew.sh]

```sh
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
follow the steps suggested by brew to config the env vars

## Warp terminal
A built-in rust-based terminal with AI integrated, helpful to ordinary developer thigs
```sh
$ brew install --cask warp
```

## Flutter
UI tool-kit for developing beatiful apps LOL
```sh
$ brew install flutter
```

here you will also need to install
- Roseta 2: to translate some flutter components process between arm and x86 architecture
```sh
$ sudo softwareupdate --install-rosetta --agree-to-license
```

- Android studio: to develop your flutter apps with
```sh
$ brew install --cask android-studio
```

- Cocoapods: to use Flutter plugins with native iOS code
flutter doc guide tell us to use the RubyGems pack manager, but I'll use brew instead
```sh
$ brew install cocoapods
```

- Xcode
download form app store

- Google chrome
```sh
$ brew install --cask google-chrome
```


- Install node
## Nest JS
```sh
$ brew install node 
```
- Install Nest globaly
```sh
npm i -g @nestjs/cli
```
# APPS for productivity
- rectangle: to manage windows
```sh
$ brew install rectangle 
```
- alt-tab: show preview and all windows, even the same app
```sh
$ brew install alt-tab 
```

- sublime text: for a similar notepad
```sh
$ brew install alt-tab 
```
# APPS for work

## Discord
```sh
$ brew install --cask discord
```

## Telegram
```sh
$ brew install --cask telegram
```

## Github desktop
```sh
$ brew install --cask github
```


