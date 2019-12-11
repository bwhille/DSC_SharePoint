# DSC_SharePoint
A SharePoint DSC

Diese DSC für SharePoint verwendet folgende DSC-Module:

    Import-DscResource -ModuleName "SharePointDSC"
    Import-DscResource -ModuleName "xDownloadFile"
    Import-DscResource -ModuleName "xDownloadISO"
    Import-DscResource -ModuleName "xPendingReboot" 

Diese können über die PS mit dem Befehl Find-Module *Modulname* | Install-Module installiert werden.

Mit Get-DSCResource kann überprüft werden, ob das Modul um System installiert wurde und welche Optionen das Modul mitbringt.
