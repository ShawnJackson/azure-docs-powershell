---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.dll-Help.xml
online version: 
schema: 2.0.0
ms.assetid: B4D60A22-E5F1-4AA9-A17E-1DF198D54D15
---

# Get-AzureVMPuppetExtension

## SYNOPSIS
Gets the Puppet extension applied on a virtual machine.

## SYNTAX

```
Get-AzureVMPuppetExtension -VM <IPersistentVM> [-Profile <AzureProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureVMPuppetExtension** cmdlet gets the Puppet extension applied on a virtual machine.

## EXAMPLES

### Example 1: Get the Puppet extension applied on a virtual machine
```
PS C:\>Get-AzureVMPuppetExtension -VM $VM
```

This command gets the Puppet extension applied on a virtual machine.

## PARAMETERS

### -VM
Specifies the persistent virtual machine object.

```yaml
Type: IPersistentVM
Parameter Sets: (All)
Aliases: InputObject

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName, ByValue)
Accept wildcard characters: False
```

### -Profile
Specifies the Azure profile from which this cmdlet reads.
If you do not specify a profile, this cmdlet reads from the local default profile.

```yaml
Type: AzureProfile
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Remove-AzureVMPuppetExtension](./Remove-AzureVMPuppetExtension.md)

[Set-AzureVMPuppetExtension](./Set-AzureVMPuppetExtension.md)


