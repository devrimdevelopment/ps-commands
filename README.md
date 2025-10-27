# ps-commands
Get-ComputerInfo | Select-Object -ExpandProperty HyperVisorPresent
Set-VMProcessor -VMName "VM_NAME" -ExposeVirtualizationExtensions $true
