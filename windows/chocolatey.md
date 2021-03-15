# Template for installing apps using PowerShell and chocolatey

## [Chocolatey](https://chocolatey.org/install) - The Package Manager for Windows

```powershell
# MUST-HAVE [general]
cohoc install k-litecodecpackmega listary f.lux recuva testdisk-photorec cloneapp sysinternals --yes
# Important
choco install windowsupdate.disableautorestart eartrumpet patch-my-pc --yes
# For games
choco install borderlessgaming playnite --yes
# Game clients
choco install origin itch goggalaxy --yes
# Hanful
choco install unchecky sandboxie.install gamesavemanager obs-studio.install dropit.install sharex streamlabs-obs powertoys fileoptimizer defraggler ultradefrag hwinfo.install pushbullet pdfxchangeeditor anydesk.install mpc-hc sumo dumo rssowl produkey.install drawio carnac virustotaluploader strokesplus.install prey -yes\
# Socials
choco install telegram.install discord.install teamspeak --yes
# For artists
choco install kuadro --yes
# git
choco install gitextensions git.install gitkraken --yes
# For programmers
choco install vscode rufus virtualbox docker-desktop --yes
```

Perhaps, I'll improve it using other solutions:

* https://github.com/sketch7/machine-setup
* https://github.com/ritasker/Chocolatey-Install-Enviroment/blob/master/Chocolatey-Setup-Env.ps1
* https://github.com/neutmute/nm-boxstarter/blob/master/base-box.ps1
* https://github.com/koppor/koppors-chocolatey-scripts/blob/master/install-koppors-autohotkey-scripts.bat