# oh-my-posh-theme

1. Install .net core PowerShell and Windows Package Manager CLI
   ```
   winget install Microsoft.PowerShell
   winget install --id Microsoft.WindowsTerminal -e
   ```
2. Install\upgrade OhMyPosh
   ```
   winget install JanDeDobbeleer.OhMyPosh -s winget
   winget upgrade JanDeDobbeleer.OhMyPosh -s winget
   ```
3. Install terminal icons
   ```
   Install-Module -Name Terminal-Icons -Repository PSGallery
   ```
4. Edit $PROFILE in windows terminal and add the following lines
   ```
   oh-my-posh --init --shell pwsh --config C:\github\prompt\poshtheme.json | Invoke-Expression
   Import-Module -Name Terminal-Icons
   ```


Use appropriate font to see the gylphs  - FiraCode Nerd Font
Restart the terminal.
