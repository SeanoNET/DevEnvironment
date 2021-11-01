# DevEnvironment
My Windows Terminal, Visual Studio Code settings, PowerShell profile and more.


# Setup

- Install [Delugia Nerd Font Powerline](https://github.com/adam7/delugia-code/releases)

Install PowerShell modules
- PowerShellGet `Install-Module -Name PowerShellGet -Force`
- PSReadLine `Install-Module PSReadLine -AllowPrerelease -Force`
- posh-git `Install-Module -Name posh-git -Force`
- DockerCompletion `Install-Module -Name DockerCompletion -Force`
- Terminal-Icons `Install-Module -Name Terminal-Icons -Force`

So we can load custom config install cli for OhMyPosh `winget install JanDeDobbeleer.OhMyPosh`

## PowerShell profile

Update your PowerShell profile by running `notepad $profile` and then copy contents of `Microsoft.PowerShell_profile.ps1`

> If you do *not* have a profile run `echo "" >> $profile`

## Credits
[My Ultimate PowerShell prompt with Oh My Posh and the Windows Terminal](https://www.hanselman.com/blog/my-ultimate-powershell-prompt-with-oh-my-posh-and-the-windows-terminal)