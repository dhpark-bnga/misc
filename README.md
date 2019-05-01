This is for FPPF-1521

$PSVersion.Table.PSVersion

Set-ExecutionPolicy -ExecutionPolicy Unrestricted -Force
Set-ExecutionPolicy -ExecutionPolicy Restricted -Force
winrm enumerate winrm/config/Listener

winrm get winrm/config/Service

winrm get winrm/config/Winrs
