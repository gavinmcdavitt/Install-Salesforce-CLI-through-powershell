# Install-Salesforce-CLI-through-powershell
This is a quick and easy way to install the salesforce CLI onto your local machine.
## 1.) Clone this repository to your local machine. 
## 2.) Run this command:
`Get-ExecutionPolicy`
### If the result is Restricted then run this command
`Set-ExecutionPolicy -ExecutionPolicy Bypass -Scope Process -Force`
### It should then say: Bypass
## 3.) Go to the directory where the powershell script *install-sfdx.ps1*
## 4.) Run this script with the administrator privileges
`./install-sfdx.ps1`
### As of August 15th 2024 this works.