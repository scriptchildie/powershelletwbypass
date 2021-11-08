# powershelletwbypass
Powershell ScriptBlock Log Bypass / ETW bypass 

This script can be used to bypass Powershell Logging. 

It is achieved by patching ntdll!EtwEventWriteTransfer. 

The bypass only works in the current session and not universally on the host. It doesn't interact with any registry values. 

