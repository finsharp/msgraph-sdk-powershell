---
external help file:
Module Name: Microsoft.Graph.Users.Calendar
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.users.calendar/new-mgusercalendarviewsinglevalueextendedproperty
schema: 2.0.0
---

# New-MgUserCalendarViewSingleValueExtendedProperty

## SYNOPSIS
Create new navigation property to singleValueExtendedProperties for users

## SYNTAX

### CreateExpanded3 (Default)
```
New-MgUserCalendarViewSingleValueExtendedProperty -EventId <String> -UserId <String> [-Id <String>]
 [-Value <String>] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Create3
```
New-MgUserCalendarViewSingleValueExtendedProperty -EventId <String> -UserId <String>
 -BodyParameter <IMicrosoftGraphSingleValueLegacyExtendedProperty> [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Create4
```
New-MgUserCalendarViewSingleValueExtendedProperty -CalendarId <String> -EventId <String> -UserId <String>
 -BodyParameter <IMicrosoftGraphSingleValueLegacyExtendedProperty> [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Create5
```
New-MgUserCalendarViewSingleValueExtendedProperty -EventId <String> -UserId <String>
 -BodyParameter <IMicrosoftGraphSingleValueLegacyExtendedProperty> [-Confirm] [-WhatIf] [<CommonParameters>]
```

### CreateExpanded4
```
New-MgUserCalendarViewSingleValueExtendedProperty -CalendarId <String> -EventId <String> -UserId <String>
 [-Id <String>] [-Value <String>] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### CreateExpanded5
```
New-MgUserCalendarViewSingleValueExtendedProperty -EventId <String> -UserId <String> [-Id <String>]
 [-Value <String>] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### CreateViaIdentity3
```
New-MgUserCalendarViewSingleValueExtendedProperty -InputObject <IUsersCalendarIdentity>
 -BodyParameter <IMicrosoftGraphSingleValueLegacyExtendedProperty> [-Confirm] [-WhatIf] [<CommonParameters>]
```

### CreateViaIdentity4
```
New-MgUserCalendarViewSingleValueExtendedProperty -InputObject <IUsersCalendarIdentity>
 -BodyParameter <IMicrosoftGraphSingleValueLegacyExtendedProperty> [-Confirm] [-WhatIf] [<CommonParameters>]
```

### CreateViaIdentity5
```
New-MgUserCalendarViewSingleValueExtendedProperty -InputObject <IUsersCalendarIdentity>
 -BodyParameter <IMicrosoftGraphSingleValueLegacyExtendedProperty> [-Confirm] [-WhatIf] [<CommonParameters>]
```

### CreateViaIdentityExpanded3
```
New-MgUserCalendarViewSingleValueExtendedProperty -InputObject <IUsersCalendarIdentity> [-Id <String>]
 [-Value <String>] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### CreateViaIdentityExpanded4
```
New-MgUserCalendarViewSingleValueExtendedProperty -InputObject <IUsersCalendarIdentity> [-Id <String>]
 [-Value <String>] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### CreateViaIdentityExpanded5
```
New-MgUserCalendarViewSingleValueExtendedProperty -InputObject <IUsersCalendarIdentity> [-Id <String>]
 [-Value <String>] [-Confirm] [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
Create new navigation property to singleValueExtendedProperties for users

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
singleValueLegacyExtendedProperty
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphSingleValueLegacyExtendedProperty
Parameter Sets: Create3, Create4, Create5, CreateViaIdentity3, CreateViaIdentity4, CreateViaIdentity5
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
Parameter Sets: Create4, CreateExpanded4
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
Parameter Sets: Create3, Create4, Create5, CreateExpanded3, CreateExpanded4, CreateExpanded5
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
Parameter Sets: CreateExpanded3, CreateExpanded4, CreateExpanded5, CreateViaIdentityExpanded3, CreateViaIdentityExpanded4, CreateViaIdentityExpanded5
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
Parameter Sets: CreateViaIdentity3, CreateViaIdentity4, CreateViaIdentity5, CreateViaIdentityExpanded3, CreateViaIdentityExpanded4, CreateViaIdentityExpanded5
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -UserId
key: user-id of user

```yaml
Type: System.String
Parameter Sets: Create3, Create4, Create5, CreateExpanded3, CreateExpanded4, CreateExpanded5
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Value
A property value.

```yaml
Type: System.String
Parameter Sets: CreateExpanded3, CreateExpanded4, CreateExpanded5, CreateViaIdentityExpanded3, CreateViaIdentityExpanded4, CreateViaIdentityExpanded5
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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphSingleValueLegacyExtendedProperty

### Microsoft.Graph.PowerShell.Models.IUsersCalendarIdentity

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphSingleValueLegacyExtendedProperty

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IMicrosoftGraphSingleValueLegacyExtendedProperty>: singleValueLegacyExtendedProperty
  - `[Id <String>]`: Read-only.
  - `[Value <String>]`: A property value.

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

