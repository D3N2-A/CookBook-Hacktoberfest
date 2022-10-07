# Powershell customisation 💻

Are you bored of classic windows terminal?

All those fancy linux terminals with cool interface makes you wanna switch?

Worry not this comprehensive guide will take you from this :

![Starting](https://raw.githubusercontent.com/D3N2-A/CookBook-Hacktoberfest/main/Powershell/img/start.webp)

To this :
![Finish](https://raw.githubusercontent.com/D3N2-A/CookBook-Hacktoberfest/main/Powershell/img/finish.png)

By the end of this guide you will also integrate various plugins into powershell such as -

- Scoop - A command-line installer
- Oh My Posh - Prompt theme engine
- Terminal Icons - Folder and file icons
- PSReadLine - Cmdlets for customizing the editing environment, used for autocompletion
- z - Directory jumper
- PSFzf - Fuzzy finder

**STEP 1**
First you have to install latest windows terminal and powershell from microsoft store (if not installed already)
The head to settings tab and your settings should look like this :
![settings](https://raw.githubusercontent.com/D3N2-A/CookBook-Hacktoberfest/main/Powershell/img/settings.png)

**STEP 2**
Install Scoop

```
> Set-ExecutionPolicy RemoteSigned -Scope CurrentUser # Optional: Needed to run a remote script the first time
> irm get.scoop.sh | iex
```

**STEP 3**
Install oh-my-posh

```

>winget install JanDeDobbeleer.OhMyPosh -s winget
```

Now Install nerd fonts from
https://github.com/ryanoasis/nerd-fonts/releases/tag/v2.2.2
I personally use _DroidSansMono_
