
# HomeBrew | NVM | Node  Installation Guide

## Homebrew install
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

### If it's your first time installing Homebrew, you'll see instructions to add Homebrew to your PATH.
```
==> Next steps:
- Add Homebrew to your PATH in /Users/lokeshsharma/.zprofile:
    echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/lokeshsharma/.zprofile
    eval "$(/opt/homebrew/bin/brew shellenv)"
```

### You need copy these two commands from your terminal and paste it like this

### Remember to put ```&&``` between the commands
```
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/lokeshsharma/.zprofile && eval "$(/opt/homebrew/bin/brew shellenv)"
```

## NVM Installation
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
```

```
nano ~/.zshrc
```

```
source ~/.zshrc
```
## Node Installation
```
nvm ls-remote
```

```
nvm install <version>
```

```
nvm use <version>
```
