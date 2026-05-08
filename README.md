# Installations

### Download
```powershell
winget install --id Git.Git -e --source winget

https://git-scm.com/install/windows
```

### App Stores
* Windows App Store - PowerShell-v7 & VSCode
* VSCode Extension Store - PowerShell, GitHub pull request

### Powershell Modules 
```powershell
install-Module Microsoft.Graph  # api for office 365. exchange, azure ad (replaces ms-online & azure-ad) 
install-Module PnP.Powershell   # sharepoint 
Install-Module ImportExcel      # manipulate excel files 
Install-Module JoinModule       # inner join, left join two objects  
Install-Module SqlServer        # talk to sql server 
```

### Windows Pptional Features
```powershell
Get-WindowsCapability -Name RSAT* -Online | Add-WindowsCapability -Online
Add-WindowsCapability -Online -Name Rsat.ActiveDirectory.DS-LDS.Tools~~~~0.0.1.0
```
