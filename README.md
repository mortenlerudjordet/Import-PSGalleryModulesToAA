# Import-PSGalleryModulesToAA

This Azure Automation Runbook imports a module and all of it's dependencies into AA from PowerShell Gallery.
This is meant to only run from an Automation account. This module can import the Az module into the Automation account.

It uses the Azure Automation RunAs Account with certificate, so this needs to be active on the account.

NOTE:
    Running this on a new AA account one must input both AutomationResourceGroupName and AutomationAccountName
