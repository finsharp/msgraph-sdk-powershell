---
external help file:
Module Name: Microsoft.Graph.Identity.DirectoryManagement
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.directorymanagement/update-mgdirectorysettingtemplatedirectorysettingtemplatedirectorysettingtemplate
schema: 2.0.0
---

# Update-MgDirectorySettingTemplateDirectorySettingTemplateDirectorySettingTemplate

## SYNOPSIS
Update entity in directorySettingTemplates

## SYNTAX

### UpdateExpanded (Default)
```
Update-MgDirectorySettingTemplateDirectorySettingTemplateDirectorySettingTemplate
 -DirectorySettingTemplateId <String> [-DeletedDateTime <DateTime>] [-Description <String>]
 [-DisplayName <String>] [-Id <String>] [-Values <IMicrosoftGraphSettingTemplateValue[]>] [-PassThru]
 [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Update
```
Update-MgDirectorySettingTemplateDirectorySettingTemplateDirectorySettingTemplate
 -DirectorySettingTemplateId <String> -BodyParameter <IMicrosoftGraphDirectorySettingTemplate> [-PassThru]
 [-Confirm] [-WhatIf] [<CommonParameters>]
```

### UpdateViaIdentity
```
Update-MgDirectorySettingTemplateDirectorySettingTemplateDirectorySettingTemplate
 -InputObject <IIdentityDirectoryManagementIdentity> -BodyParameter <IMicrosoftGraphDirectorySettingTemplate>
 [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### UpdateViaIdentityExpanded
```
Update-MgDirectorySettingTemplateDirectorySettingTemplateDirectorySettingTemplate
 -InputObject <IIdentityDirectoryManagementIdentity> [-DeletedDateTime <DateTime>] [-Description <String>]
 [-DisplayName <String>] [-Id <String>] [-Values <IMicrosoftGraphSettingTemplateValue[]>] [-PassThru]
 [-Confirm] [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
Update entity in directorySettingTemplates

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
Represents an Azure Active Directory object.
The directoryObject type is the base type for many other directory entity types.
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphDirectorySettingTemplate
Parameter Sets: Update, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -DeletedDateTime
.

```yaml
Type: System.DateTime
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Description
.

```yaml
Type: System.String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DirectorySettingTemplateId
key: directorySettingTemplate-id of directorySettingTemplate

```yaml
Type: System.String
Parameter Sets: Update, UpdateExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DisplayName
.

```yaml
Type: System.String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Id
Read-only.

```yaml
Type: System.String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
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
Parameter Sets: UpdateViaIdentity, UpdateViaIdentityExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -PassThru
Returns true when the command succeeds

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Values
.
To construct, see NOTES section for VALUES properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphSettingTemplateValue[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphDirectorySettingTemplate

## OUTPUTS

### System.Boolean

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IMicrosoftGraphDirectorySettingTemplate>: Represents an Azure Active Directory object. The directoryObject type is the base type for many other directory entity types.
  - `[DeletedDateTime <DateTime?>]`: 
  - `[Id <String>]`: Read-only.
  - `[Description <String>]`: 
  - `[DisplayName <String>]`: 
  - `[Values <IMicrosoftGraphSettingTemplateValue[]>]`: 
    - `[DefaultValue <String>]`: Default value for the setting.
    - `[Description <String>]`: Description of the setting.
    - `[Name <String>]`: Name of the setting.
    - `[Type <String>]`: Type of the setting.

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

VALUES <IMicrosoftGraphSettingTemplateValue[]>: .
  - `[DefaultValue <String>]`: Default value for the setting.
  - `[Description <String>]`: Description of the setting.
  - `[Name <String>]`: Name of the setting.
  - `[Type <String>]`: Type of the setting.

## RELATED LINKS
