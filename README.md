# Azure-Intune-Export-DeviceConfiguration-Decrypts

This exports Device Configuration Policies in Intune.

I have manipulated code from these repositories:
https://github.com/DeployWindowsCom/DeployWindows-Scripts/blob/master/Intune/Graph%20samples/DeviceConfiguration/DeviceConfiguration_Get.ps1
https://github.com/microsoftgraph/powershell-intune-samples/tree/master/DeviceConfiguration

- Microsoft's repo did not decrypt the values that were encrypted in the configuration. This script does.
- DeplyoWindowsCom's repo did not export using unicode which broke policies that used the  character required in some policies
