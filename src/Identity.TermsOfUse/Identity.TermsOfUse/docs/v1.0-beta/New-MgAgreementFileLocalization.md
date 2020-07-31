---
external help file:
Module Name: Microsoft.Graph.Identity.TermsOfUse
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.termsofuse/new-mgagreementfilelocalization
schema: 2.0.0
---

# New-MgAgreementFileLocalization

## SYNOPSIS
Create new navigation property to localizations for agreements

## SYNTAX

### CreateExpanded (Default)
```
New-MgAgreementFileLocalization -AgreementId <String> [-FileDataDataInputFile <String>] [-FileName <String>]
 [-Id <String>] [-IsDefault] [-Language <String>] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Create
```
New-MgAgreementFileLocalization -AgreementId <String>
 -BodyParameter <IMicrosoftGraphAgreementFileLocalization> [-Confirm] [-WhatIf] [<CommonParameters>]
```

### CreateViaIdentity
```
New-MgAgreementFileLocalization -InputObject <IIdentityTermsOfUseIdentity>
 -BodyParameter <IMicrosoftGraphAgreementFileLocalization> [-Confirm] [-WhatIf] [<CommonParameters>]
```

### CreateViaIdentityExpanded
```
New-MgAgreementFileLocalization -InputObject <IIdentityTermsOfUseIdentity> [-FileDataDataInputFile <String>]
 [-FileName <String>] [-Id <String>] [-IsDefault] [-Language <String>] [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

## DESCRIPTION
Create new navigation property to localizations for agreements

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

### -AgreementId
key: agreement-id of agreement

```yaml
Type: System.String
Parameter Sets: Create, CreateExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
agreementFileLocalization
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphAgreementFileLocalization
Parameter Sets: Create, CreateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -FileDataDataInputFile
Input File for FileDataData (.)

```yaml
Type: System.String
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -FileName
.

```yaml
Type: System.String
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
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
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
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
Type: Microsoft.Graph.PowerShell.Models.IIdentityTermsOfUseIdentity
Parameter Sets: CreateViaIdentity, CreateViaIdentityExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -IsDefault
.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Language
.

```yaml
Type: System.String
Parameter Sets: CreateExpanded, CreateViaIdentityExpanded
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

### Microsoft.Graph.PowerShell.Models.IIdentityTermsOfUseIdentity

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphAgreementFileLocalization

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphAgreementFileLocalization

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IMicrosoftGraphAgreementFileLocalization>: agreementFileLocalization
  - `[FileDataData <Byte[]>]`: 
  - `[FileName <String>]`: 
  - `[IsDefault <Boolean?>]`: 
  - `[Language <String>]`: 
  - `[Id <String>]`: Read-only.

INPUTOBJECT <IIdentityTermsOfUseIdentity>: Identity Parameter
  - `[AgreementAcceptanceId <String>]`: key: agreementAcceptance-id of agreementAcceptance
  - `[AgreementFileLocalizationId <String>]`: key: agreementFileLocalization-id of agreementFileLocalization
  - `[AgreementId <String>]`: key: agreement-id of agreement
  - `[UserId <String>]`: key: user-id of user

## RELATED LINKS
