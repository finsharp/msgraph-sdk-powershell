---
external help file:
Module Name: Microsoft.Graph.Groups
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.groups/new-mggroupsettingtemplategroupsettingtemplategroupsettingtemplate
schema: 2.0.0
---

# New-MgGroupSettingTemplateGroupSettingTemplateGroupSettingTemplate

## SYNOPSIS
Add new entity to groupSettingTemplates

## SYNTAX

### CreateExpanded (Default)
```
New-MgGroupSettingTemplateGroupSettingTemplateGroupSettingTemplate [-DeletedDateTime <DateTime>]
 [-Description <String>] [-DisplayName <String>] [-Id <String>]
 [-Values <IMicrosoftGraphSettingTemplateValue[]>] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Create
```
New-MgGroupSettingTemplateGroupSettingTemplateGroupSettingTemplate
 -BodyParameter <IMicrosoftGraphGroupSettingTemplate> [-Confirm] [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
Add new entity to groupSettingTemplates

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
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphGroupSettingTemplate
Parameter Sets: Create
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
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Description
Description of the template.

```yaml
Type: System.String
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DisplayName
Display name of the template.

```yaml
Type: System.String
Parameter Sets: CreateExpanded
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
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Values
Collection of settingTemplateValues that list the set of available settings, defaults and types that make up this template.
To construct, see NOTES section for VALUES properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphSettingTemplateValue[]
Parameter Sets: CreateExpanded
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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphGroupSettingTemplate

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphGroupSettingTemplate

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IMicrosoftGraphGroupSettingTemplate>: Represents an Azure Active Directory object. The directoryObject type is the base type for many other directory entity types.
  - `[DeletedDateTime <DateTime?>]`: 
  - `[Id <String>]`: Read-only.
  - `[Description <String>]`: Description of the template.
  - `[DisplayName <String>]`: Display name of the template.
  - `[Values <IMicrosoftGraphSettingTemplateValue[]>]`: Collection of settingTemplateValues that list the set of available settings, defaults and types that make up this template.
    - `[DefaultValue <String>]`: Default value for the setting.
    - `[Description <String>]`: Description of the setting.
    - `[Name <String>]`: Name of the setting.
    - `[Type <String>]`: Type of the setting.

VALUES <IMicrosoftGraphSettingTemplateValue[]>: Collection of settingTemplateValues that list the set of available settings, defaults and types that make up this template.
  - `[DefaultValue <String>]`: Default value for the setting.
  - `[Description <String>]`: Description of the setting.
  - `[Name <String>]`: Name of the setting.
  - `[Type <String>]`: Type of the setting.

## RELATED LINKS
