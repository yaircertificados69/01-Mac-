- #### Brew

> - Gestor de paquetes

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

```
 brew install wget
```

```
 cd /usr/local
find Cellar
Cellar/wget/1.16.1
Cellar/wget/1.16.1/bin/wget
Cellar/wget/1.16.1/share/man/man1/wget.1
```

```
ls -l bin
bin/wget -> ../Cellar/wget/1.16.1/bin/wget
```

-------------------------------------

* ### Fonts

```
git clone https://github.com/powerline/fonts.git
cd fonts
./install.sh
```

sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

--------------------------------------------------------------

- #### Terminales

> - Iterminal comandos 

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"----------------------------------------------------
```

------------------------

- # Oh my  zsh

> - zsh
> 
> - *oh my zsh*

```
brew install zsh

chsh -s $(which zsh)

zsh --version
```

> powerline10k
> 
> plugins

* ## Oh my Zsh

```
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

- ## PowerLevel10k

```
gh repo clone romkatv/powerlevel10k $ZSH_CUSTOM/themes/powerlevel10k


git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k
```

```
brew install romkatv/powerlevel10k/powerlevel10k
echo "source $(brew --prefix)/opt/powerlevel10k/powerlevel10k.zsh-theme" >>~/.zshrc
```

```
p10k configure
```

---------------

> ##### Powerline10k  *zshrc*
> 
> ```
> ZSH_THEME="powerlevel10k/powerlevel10k"
> ```

---

### Plugins (Syntaxys Suggestion)

```
# gh cli
gh repo clone zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

# git
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

```
# gh cli
gh repo clone zsh-users/zsh-syntax-highlighting ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

# git
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

---

## ITS Tools

```
sudo gem install colorls
```

```
brew install exa
```

```
# via npm
npm install -g secman

# via script
curl -fsSL https://cli.secman.dev | bash
```

> ### Secrets Manager
> 
> ```
> # via npm
> npm install -g secman
> 
> # via script
> curl -fsSL https://cli.secman.dev | 
> bash
> ```

### 

> #### file transfer app
> 
> ```
> # via npm
> npm install -g secman
> 
> # via script
> curl -fsSL https://cli.secman.dev | 
> bash
> ```

---

> ##### Plugins*zshrc*
> 
> ```
> ZSH_THEME="powerlevel10k/powerlevel10k"
> ```

---

#### Config Zsh source

In `~/.zshrc` file replace the line starting with `plugins=()` to below line.  

```
plugins=( git zsh-syntax-highlighting zsh-autosuggestions )
```

> colorls  

```
if [ -x "$(command -v colorls)" ]; then    alias ls="colorls"
    alias la="colorls -al"
fi
```

> or exa  

```
if [ -x "$(command -v exa)" ]; then    alias ls="exa"
    alias la="exa --long --all --group"
fi
```

```
source ~/.zshrc
```

--------------------

![Alt Text](https://res.cloudinary.com/practicaldev/image/fetch/s--kwScx4A6--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/i/7yxpyhy9lj36ks178ywt.png)

----------------

# Android Studio

> - Andrid Studio
> 
> - Command line tools only

```
https://r2---sn-9gv7lnes.gvt1.com/edgedl/android/studio/install/2022.1.1.20/android-studio-2022.1.1.20-mac.dmg?mh=mJ&pl=54&shardbypass=sd&redirect_counter=1&cm2rm=sn-hxb5j5cax-9gv67e&req_id=fdeb6b4a652f2539&cms_redirect=yes&ipbypass=yes&mip=2806:264:440c:8129:a523:81c9:5936:a549&mm=42&mn=sn-9gv7lnes&ms=onc&mt=1675492844&mv=m&mvi=2&rmhost=r3---sn-9gv7lnes.gvt1.com&smhost=r1---sn-9gv7lnle.gvt1.comhttps://dl.google.com/android/repository/commandlinetools-mac-9477386_latest.zip
```

```
https://dl.google.com/android/repository/commandlinetools-mac-9477386_latest.zip
```

-----------------------------

## Mac OS  *React Native Enviroment*

- Andrid Studio
* Brew install

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

```ba
 brew install wget
```

```
npm install -g react-native-cli
brew install yarn


sudo gem install cocoapods
```

* Devices 

* brew install watchman

* Gestor de paquetes

* brew install node

### Config Android Home

* # Android Home

> `.bashrc`
> 
> `.zshrc`
> 
> ```
> export ANDROID_HOME=$HOME/Library/Android/sdkexport PATH=$PATH:$ANDROID_HOME/emulatorexport PATH=$PATH:$ANDROID_HOME/toolsexport PATH=$PATH:$ANDROID_HOME/tools/binexport PATH=$PATH:$ANDROID_HOME/platform-tools
> ```

----------------

### *React Native OPENJDK*

```javscript
brew install --cask adopt
openjdk/openjdk/adoptopenjdk8
```

```javscript
 brew tap AdoptOpenJDK/openjdk
 brew install --cask adoptopenjdk8
```

```javscript
    brew tap AdoptOpenJDK/openjdk
    brew install --cask adoptopenjdk8
```

> `brew tap AdoptOpenJDK/openjdk`  
> `brew install --cask adoptopenjdk8`

> `brew tap AdoptOpenJDK/openjdk`  
> `brew install --cask adoptopenjdk8`

### Roseta oftware

```
softwareupdate --install-rosetta
```

```
brew install cocoapods  
sudo gem install ffi
```

npm install -g react-native-cli

* 

## React  Native   *CLI*

```text
npx react-native init FirstProject
```

> ##### React Native  *CLI*
> 
> ```text
> npx react-native init FirstProject
> ```

> #### React Native *CLI*
> 
> ```text
> cd FirstProject
> npx react-native run-ios
> ```

----------------------------

* # Xcode

## >>  Xcode Command Line Tools from a Command Prompt

- `clang` – a compiler that turns source code into an executable program
- `gcc` – the GNU compiler
- `git` – the save-as-you-go version control system

`xcode-select --install`

```
 xcode-select --install
```

```
xcode-select -p
```

```
npx react-native init AwesomeProject
```

xcode-select -p

xcode-select --install

`xcode-select --install`

------------------

# React Native

### 

## Node & Watchman

```
brew install node
brew install watchman
```

> ## Creating a new application
> 
> ```
> npm uninstall -g react-native-cli @react-native-community/cli
> ```

```
npx react-native init AwesomeProject
```

```
npx react-native init AwesomeProject --version X.XX.X
```

```
npx react-native start
```

```
npx react-native run-ios
```

![](C:\Users\1l1l1l\AppData\Roaming\marktext\images\2023-02-04-01-50-37-GettingStartediOSSuccess-e6dd7fc2baa303d1f30373d996a6e51d.png)
