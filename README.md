# Import-PSGalleryModulesToAA

This Azure Automation Runbook imports a module and all of it's dependencies into AA from PowerShell Gallery.
This is meant to only run from an Automation account. This module can import the Az module into the Automation account.

Update: Now supports both 5.1 and 7.2 runtime for modules

NOTE:
    As this introduces runtime version support, before running make sure Az.Accounts, Az.Automation and Az.Resources are updated to the latest version
    on both 5.1 and 7.2 runtime before running this.
