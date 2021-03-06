---
external help file:
Module Name: Microsoft.Graph.Users.Calendar
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.users.calendar/update-mgusercalendarviewextension
schema: 2.0.0
---

# Update-MgUserCalendarViewExtension

## SYNOPSIS
Update the navigation property extensions in users

## SYNTAX

### UpdateExpanded3 (Default)
```
Update-MgUserCalendarViewExtension -EventId <String> -ExtensionId <String> -UserId <String> [-Id <String>]
 [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Update3
```
Update-MgUserCalendarViewExtension -EventId <String> -ExtensionId <String> -UserId <String>
 -BodyParameter <IMicrosoftGraphExtension> [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Update4
```
Update-MgUserCalendarViewExtension -CalendarId <String> -EventId <String> -ExtensionId <String>
 -UserId <String> -BodyParameter <IMicrosoftGraphExtension> [-PassThru] [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

### Update5
```
Update-MgUserCalendarViewExtension -EventId <String> -ExtensionId <String> -UserId <String>
 -BodyParameter <IMicrosoftGraphExtension> [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### UpdateExpanded4
```
Update-MgUserCalendarViewExtension -CalendarId <String> -EventId <String> -ExtensionId <String>
 -UserId <String> [-Id <String>] [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### UpdateExpanded5
```
Update-MgUserCalendarViewExtension -EventId <String> -ExtensionId <String> -UserId <String> [-Id <String>]
 [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### UpdateViaIdentity3
```
Update-MgUserCalendarViewExtension -InputObject <IUsersCalendarIdentity>
 -BodyParameter <IMicrosoftGraphExtension> [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### UpdateViaIdentity4
```
Update-MgUserCalendarViewExtension -InputObject <IUsersCalendarIdentity>
 -BodyParameter <IMicrosoftGraphExtension> [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### UpdateViaIdentity5
```
Update-MgUserCalendarViewExtension -InputObject <IUsersCalendarIdentity>
 -BodyParameter <IMicrosoftGraphExtension> [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### UpdateViaIdentityExpanded3
```
Update-MgUserCalendarViewExtension -InputObject <IUsersCalendarIdentity> [-Id <String>] [-PassThru] [-Confirm]
 [-WhatIf] [<CommonParameters>]
```

### UpdateViaIdentityExpanded4
```
Update-MgUserCalendarViewExtension -InputObject <IUsersCalendarIdentity> [-Id <String>] [-PassThru] [-Confirm]
 [-WhatIf] [<CommonParameters>]
```

### UpdateViaIdentityExpanded5
```
Update-MgUserCalendarViewExtension -InputObject <IUsersCalendarIdentity> [-Id <String>] [-PassThru] [-Confirm]
 [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
Update the navigation property extensions in users

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
extension
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphExtension
Parameter Sets: Update3, Update4, Update5, UpdateViaIdentity3, UpdateViaIdentity4, UpdateViaIdentity5
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -CalendarId
key: calendar-id of calendar

```yaml
Type: System.String
Parameter Sets: Update4, UpdateExpanded4
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EventId
key: event-id of event

```yaml
Type: System.String
Parameter Sets: Update3, Update4, Update5, UpdateExpanded3, UpdateExpanded4, UpdateExpanded5
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ExtensionId
key: extension-id of extension

```yaml
Type: System.String
Parameter Sets: Update3, Update4, Update5, UpdateExpanded3, UpdateExpanded4, UpdateExpanded5
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Id
Read-only.

```yaml
Type: System.String
Parameter Sets: UpdateExpanded3, UpdateExpanded4, UpdateExpanded5, UpdateViaIdentityExpanded3, UpdateViaIdentityExpanded4, UpdateViaIdentityExpanded5
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
Type: Microsoft.Graph.PowerShell.Models.IUsersCalendarIdentity
Parameter Sets: UpdateViaIdentity3, UpdateViaIdentity4, UpdateViaIdentity5, UpdateViaIdentityExpanded3, UpdateViaIdentityExpanded4, UpdateViaIdentityExpanded5
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

### -UserId
key: user-id of user

```yaml
Type: System.String
Parameter Sets: Update3, Update4, Update5, UpdateExpanded3, UpdateExpanded4, UpdateExpanded5
Aliases:

Required: True
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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphExtension

### Microsoft.Graph.PowerShell.Models.IUsersCalendarIdentity

## OUTPUTS

### System.Boolean

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IMicrosoftGraphExtension>: extension
  - `[Id <String>]`: Read-only.

INPUTOBJECT <IUsersCalendarIdentity>: Identity Parameter
  - `[AttachmentId <String>]`: key: attachment-id of attachment
  - `[CalendarGroupId <String>]`: key: calendarGroup-id of calendarGroup
  - `[CalendarId <String>]`: key: calendar-id of calendar
  - `[CalendarPermissionId <String>]`: key: calendarPermission-id of calendarPermission
  - `[EventId <String>]`: key: event-id of event
  - `[EventId1 <String>]`: key: event-id of event
  - `[ExtensionId <String>]`: key: extension-id of extension
  - `[MultiValueLegacyExtendedPropertyId <String>]`: key: multiValueLegacyExtendedProperty-id of multiValueLegacyExtendedProperty
  - `[SingleValueLegacyExtendedPropertyId <String>]`: key: singleValueLegacyExtendedProperty-id of singleValueLegacyExtendedProperty
  - `[UserId <String>]`: key: user-id of user

## RELATED LINKS

