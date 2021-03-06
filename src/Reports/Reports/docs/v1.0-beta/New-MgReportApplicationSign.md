---
external help file:
Module Name: Microsoft.Graph.Reports
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.reports/new-mgreportapplicationsign
schema: 2.0.0
---

# New-MgReportApplicationSign

## SYNOPSIS
Create new navigation property to applicationSignInDetailedSummary for reports

## SYNTAX

### CreateExpanded (Default)
```
New-MgReportApplicationSign [-AggregatedEventDateTime <DateTime>] [-AppDisplayName <String>] [-AppId <String>]
 [-Id <String>] [-SignInCount <Int64>] [-StatusAdditionalDetails <String>] [-StatusErrorCode <Int32>]
 [-StatusFailureReason <String>] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Create
```
New-MgReportApplicationSign -BodyParameter <IMicrosoftGraphApplicationSignInDetailedSummary> [-Confirm]
 [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
Create new navigation property to applicationSignInDetailedSummary for reports

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

### -AggregatedEventDateTime
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

### -AppDisplayName
.

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

### -AppId
.

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

### -BodyParameter
applicationSignInDetailedSummary
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphApplicationSignInDetailedSummary
Parameter Sets: Create
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
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

### -SignInCount
.

```yaml
Type: System.Int64
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -StatusAdditionalDetails
Provides additional details on the sign-in activity

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

### -StatusErrorCode
Provides the 5-6digit error code that's generated during a sign-in failure.
Check out the list of error codes and messages.

```yaml
Type: System.Int32
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -StatusFailureReason
Provides the error message or the reason for failure for the corresponding sign-in activity.
Check out the list of error codes and messages.

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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphApplicationSignInDetailedSummary

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphApplicationSignInDetailedSummary

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IMicrosoftGraphApplicationSignInDetailedSummary>: applicationSignInDetailedSummary
  - `[Id <String>]`: Read-only.
  - `[AggregatedEventDateTime <DateTime?>]`: 
  - `[AppDisplayName <String>]`: 
  - `[AppId <String>]`: 
  - `[SignInCount <Int64?>]`: 
  - `[StatusAdditionalDetails <String>]`: Provides additional details on the sign-in activity
  - `[StatusErrorCode <Int32?>]`: Provides the 5-6digit error code that's generated during a sign-in failure. Check out the list of error codes and messages.
  - `[StatusFailureReason <String>]`: Provides the error message or the reason for failure for the corresponding sign-in activity. Check out the list of error codes and messages.

## RELATED LINKS

