---
external help file:
Module Name: Microsoft.Graph.Reports
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.reports/get-mgreportemailactivityuserdetailfe32
schema: 2.0.0
---

# Get-MgReportEmailActivityUserDetailFe32

## SYNOPSIS
Invoke function getEmailActivityUserDetail

## SYNTAX

### Get1 (Default)
```
Get-MgReportEmailActivityUserDetailFe32 -Date <DateTime> [<CommonParameters>]
```

### GetViaIdentity1
```
Get-MgReportEmailActivityUserDetailFe32 -InputObject <IReportsIdentity> [<CommonParameters>]
```

## DESCRIPTION
Invoke function getEmailActivityUserDetail

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

### -Date
.

```yaml
Type: System.DateTime
Parameter Sets: Get1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InputObject
Identity Parameter
To construct, see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IReportsIdentity
Parameter Sets: GetViaIdentity1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Graph.PowerShell.Models.IReportsIdentity

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphEmailActivityUserDetail

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


INPUTOBJECT <IReportsIdentity>: Identity Parameter
  - `[ApplicationSignInDetailedSummaryId <String>]`: key: applicationSignInDetailedSummary-id of applicationSignInDetailedSummary
  - `[CredentialUserRegistrationDetailsId <String>]`: key: credentialUserRegistrationDetails-id of credentialUserRegistrationDetails
  - `[Date <DateTime?>]`: 
  - `[Filter <String>]`: 
  - `[Period <String>]`: 
  - `[PrintUsageSummaryByPrinterId <String>]`: key: PrintUsageSummaryByPrinter-id of PrintUsageSummaryByPrinter
  - `[PrintUsageSummaryByUserId <String>]`: key: PrintUsageSummaryByUser-id of PrintUsageSummaryByUser
  - `[Skip <Int32?>]`: 
  - `[SkipToken <String>]`: 
  - `[Top <Int32?>]`: 
  - `[UserCredentialUsageDetailsId <String>]`: key: userCredentialUsageDetails-id of userCredentialUsageDetails

## RELATED LINKS

