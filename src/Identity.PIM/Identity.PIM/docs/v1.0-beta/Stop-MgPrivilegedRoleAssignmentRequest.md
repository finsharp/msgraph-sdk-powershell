---
external help file:
Module Name: Microsoft.Graph.Identity.PIM
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.pim/stop-mgprivilegedroleassignmentrequest
schema: 2.0.0
---

# Stop-MgPrivilegedRoleAssignmentRequest

## SYNOPSIS
Invoke action cancel

## SYNTAX

### Cancel (Default)
```
Stop-MgPrivilegedRoleAssignmentRequest -PrivilegedRoleAssignmentRequestId <String> [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

### CancelViaIdentity
```
Stop-MgPrivilegedRoleAssignmentRequest -InputObject <IIdentityPimIdentity> [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

## DESCRIPTION
Invoke action cancel

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

### -InputObject
Identity Parameter
To construct, see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IIdentityPimIdentity
Parameter Sets: CancelViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -PrivilegedRoleAssignmentRequestId
key: privilegedRoleAssignmentRequest-id of privilegedRoleAssignmentRequest

```yaml
Type: System.String
Parameter Sets: Cancel
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

### Microsoft.Graph.PowerShell.Models.IIdentityPimIdentity

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphPrivilegedRoleAssignmentRequest

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


INPUTOBJECT <IIdentityPimIdentity>: Identity Parameter
  - `[GovernanceResourceId <String>]`: key: governanceResource-id of governanceResource
  - `[GovernanceRoleAssignmentId <String>]`: key: governanceRoleAssignment-id of governanceRoleAssignment
  - `[GovernanceRoleAssignmentRequestId <String>]`: key: governanceRoleAssignmentRequest-id of governanceRoleAssignmentRequest
  - `[GovernanceRoleDefinitionId <String>]`: key: governanceRoleDefinition-id of governanceRoleDefinition
  - `[GovernanceRoleSettingId <String>]`: key: governanceRoleSetting-id of governanceRoleSetting
  - `[PrivilegedAccessId <String>]`: key: privilegedAccess-id of privilegedAccess
  - `[PrivilegedApprovalId <String>]`: key: privilegedApproval-id of privilegedApproval
  - `[PrivilegedOperationEventId <String>]`: key: privilegedOperationEvent-id of privilegedOperationEvent
  - `[PrivilegedRoleAssignmentId <String>]`: key: privilegedRoleAssignment-id of privilegedRoleAssignment
  - `[PrivilegedRoleAssignmentRequestId <String>]`: key: privilegedRoleAssignmentRequest-id of privilegedRoleAssignmentRequest
  - `[PrivilegedRoleId <String>]`: key: privilegedRole-id of privilegedRole

## RELATED LINKS
