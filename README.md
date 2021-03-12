# Import-PSGalleryModulesToAA

This Azure Automation Runbook imports a module and all of it's dependencies into AA from PowerShell Gallery.
This is meant to only run from an Automation account. This module can import the Az module into the Automation account.

NOTE:
    Running this on a new AA account one must input both AutomationResourceGroupName and AutomationAccountName
