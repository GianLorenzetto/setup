# PowerShell Config

### Aliases

Drop the following into profile ...
``` Posh
# My functions for complex aliasa
function Show-AllChildren {ls -force}
function ChangePath-ToWorking {cd C:\Working}
 
# My aliases
Set-Alias subl 'C:\Program Files\Sublime Text 3\subl.exe'
Set-Alias lsa Show-AllChildren
Set-Alias cdw ChangePath-ToWorking
```