---
external help file:
Module Name: Microsoft.Graph.Identity.DirectoryManagement
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.directorymanagement/confirm-mgcontractmembergroup
schema: 2.0.0
---

# Confirm-MgContractMemberGroup

## SYNOPSIS
Invoke action checkMemberGroups

## SYNTAX

### CheckExpanded (Default)
```
Confirm-MgContractMemberGroup -ContractId <String> [-GroupIds <String[]>] [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

### Check
```
Confirm-MgContractMemberGroup -ContractId <String>
 -BodyParameter <IPaths30M7S8ContractsContractIdMicrosoftGraphCheckmembergroupsPostRequestbodyContentApplicationJsonSchema>
 [-Confirm] [-WhatIf] [<CommonParameters>]
```

### CheckViaIdentity
```
Confirm-MgContractMemberGroup -InputObject <IIdentityDirectoryManagementIdentity>
 -BodyParameter <IPaths30M7S8ContractsContractIdMicrosoftGraphCheckmembergroupsPostRequestbodyContentApplicationJsonSchema>
 [-Confirm] [-WhatIf] [<CommonParameters>]
```

### CheckViaIdentityExpanded
```
Confirm-MgContractMemberGroup -InputObject <IIdentityDirectoryManagementIdentity> [-GroupIds <String[]>]
 [-Confirm] [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
Invoke action checkMemberGroups

## EXAMPLES

### Example 1: {{ Add title here }}
```powershell
PS C:\> {{ Add code here }}

{{ Add output here }}
```

{{ Add description here }}

### Example 2: {{ Add title here }}
```powershell
PS C:\> {{ Add code here }}

{{ Add output here }}
```

{{ Add description here }}

## PARAMETERS

### -BodyParameter
.
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IPaths30M7S8ContractsContractIdMicrosoftGraphCheckmembergroupsPostRequestbodyContentApplicationJsonSchema
Parameter Sets: Check, CheckViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ContractId
key: contract-id of contract

```yaml
Type: System.String
Parameter Sets: Check, CheckExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -GroupIds
.

```yaml
Type: System.String[]
Parameter Sets: CheckExpanded, CheckViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InputObject
Identity Parameter
To construct, see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IIdentityDirectoryManagementIdentity
Parameter Sets: CheckViaIdentity, CheckViaIdentityExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Graph.PowerShell.Models.IIdentityDirectoryManagementIdentity

### Microsoft.Graph.PowerShell.Models.IPaths30M7S8ContractsContractIdMicrosoftGraphCheckmembergroupsPostRequestbodyContentApplicationJsonSchema

## OUTPUTS

### System.String

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IPaths30M7S8ContractsContractIdMicrosoftGraphCheckmembergroupsPostRequestbodyContentApplicationJsonSchema>: .
  - `[GroupIds <String[]>]`: 

INPUTOBJECT <IIdentityDirectoryManagementIdentity>: Identity Parameter
  - `[AdministrativeUnitId <String>]`: key: administrativeUnit-id of administrativeUnit
  - `[CommandId <String>]`: key: command-id of command
  - `[ContractId <String>]`: key: contract-id of contract
  - `[DeviceId <String>]`: key: device-id of device
  - `[DirectoryObjectId <String>]`: key: directoryObject-id of directoryObject
  - `[DirectoryRoleId <String>]`: key: directoryRole-id of directoryRole
  - `[DirectoryRoleTemplateId <String>]`: key: directoryRoleTemplate-id of directoryRoleTemplate
  - `[DirectorySettingId <String>]`: key: directorySetting-id of directorySetting
  - `[DirectorySettingTemplateId <String>]`: key: directorySettingTemplate-id of directorySettingTemplate
  - `[DomainDnsRecordId <String>]`: key: domainDnsRecord-id of domainDnsRecord
  - `[DomainId <String>]`: key: domain-id of domain
  - `[ExtensionId <String>]`: key: extension-id of extension
  - `[FeatureRolloutPolicyId <String>]`: key: featureRolloutPolicy-id of featureRolloutPolicy
  - `[OrgContactId <String>]`: key: orgContact-id of orgContact
  - `[ScopedRoleMembershipId <String>]`: key: scopedRoleMembership-id of scopedRoleMembership
  - `[SubscribedSkuId <String>]`: key: subscribedSku-id of subscribedSku
  - `[UserId <String>]`: key: user-id of user

## RELATED LINKS
