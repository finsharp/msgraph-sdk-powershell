---
external help file:
Module Name: Microsoft.Graph.DevicesApps.DeviceAppManagement
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicesapps.deviceappmanagement/set-mgdeviceappmanagementmobileappconfiguration
schema: 2.0.0
---

# Set-MgDeviceAppManagementMobileAppConfiguration

## SYNOPSIS
Invoke action assign

## SYNTAX

### AssignExpanded1 (Default)
```
Set-MgDeviceAppManagementMobileAppConfiguration -ManagedDeviceMobileAppConfigurationId <String>
 [-Assignments <IMicrosoftGraphManagedDeviceMobileAppConfigurationAssignment[]>] [-PassThru] [-Confirm]
 [-WhatIf] [<CommonParameters>]
```

### Assign1
```
Set-MgDeviceAppManagementMobileAppConfiguration -ManagedDeviceMobileAppConfigurationId <String>
 -BodyParameter <IPaths1Pwcjs5DeviceappmanagementMobileappconfigurationsManageddevicemobileappconfigurationIdMicrosoftGraphAssignPostRequestbodyContentApplicationJsonSchema>
 [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### AssignViaIdentity1
```
Set-MgDeviceAppManagementMobileAppConfiguration -InputObject <IDevicesAppsDeviceAppManagementIdentity>
 -BodyParameter <IPaths1Pwcjs5DeviceappmanagementMobileappconfigurationsManageddevicemobileappconfigurationIdMicrosoftGraphAssignPostRequestbodyContentApplicationJsonSchema>
 [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### AssignViaIdentityExpanded1
```
Set-MgDeviceAppManagementMobileAppConfiguration -InputObject <IDevicesAppsDeviceAppManagementIdentity>
 [-Assignments <IMicrosoftGraphManagedDeviceMobileAppConfigurationAssignment[]>] [-PassThru] [-Confirm]
 [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
Invoke action assign

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

### -Assignments
.
To construct, see NOTES section for ASSIGNMENTS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphManagedDeviceMobileAppConfigurationAssignment[]
Parameter Sets: AssignExpanded1, AssignViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
.
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IPaths1Pwcjs5DeviceappmanagementMobileappconfigurationsManageddevicemobileappconfigurationIdMicrosoftGraphAssignPostRequestbodyContentApplicationJsonSchema
Parameter Sets: Assign1, AssignViaIdentity1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -InputObject
Identity Parameter
To construct, see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IDevicesAppsDeviceAppManagementIdentity
Parameter Sets: AssignViaIdentity1, AssignViaIdentityExpanded1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ManagedDeviceMobileAppConfigurationId
key: managedDeviceMobileAppConfiguration-id of managedDeviceMobileAppConfiguration

```yaml
Type: System.String
Parameter Sets: Assign1, AssignExpanded1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
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

### Microsoft.Graph.PowerShell.Models.IDevicesAppsDeviceAppManagementIdentity

### Microsoft.Graph.PowerShell.Models.IPaths1Pwcjs5DeviceappmanagementMobileappconfigurationsManageddevicemobileappconfigurationIdMicrosoftGraphAssignPostRequestbodyContentApplicationJsonSchema

## OUTPUTS

### System.Boolean

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


ASSIGNMENTS <IMicrosoftGraphManagedDeviceMobileAppConfigurationAssignment[]>: .
  - `[Id <String>]`: Read-only.
  - `[Target <IMicrosoftGraphDeviceAndAppManagementAssignmentTarget>]`: deviceAndAppManagementAssignmentTarget

BODYPARAMETER <IPaths1Pwcjs5DeviceappmanagementMobileappconfigurationsManageddevicemobileappconfigurationIdMicrosoftGraphAssignPostRequestbodyContentApplicationJsonSchema>: .
  - `[Assignments <IMicrosoftGraphManagedDeviceMobileAppConfigurationAssignment[]>]`: 
    - `[Id <String>]`: Read-only.
    - `[Target <IMicrosoftGraphDeviceAndAppManagementAssignmentTarget>]`: deviceAndAppManagementAssignmentTarget

INPUTOBJECT <IDevicesAppsDeviceAppManagementIdentity>: Identity Parameter
  - `[AndroidManagedAppProtectionId <String>]`: key: androidManagedAppProtection-id of androidManagedAppProtection
  - `[BundleId <String>]`: 
  - `[Count <Int64?>]`: 
  - `[DefaultManagedAppProtectionId <String>]`: key: defaultManagedAppProtection-id of defaultManagedAppProtection
  - `[DeviceAppManagementTaskId <String>]`: key: deviceAppManagementTask-id of deviceAppManagementTask
  - `[DeviceId <String>]`: 
  - `[DeviceInstallStateId <String>]`: key: deviceInstallState-id of deviceInstallState
  - `[EnterpriseCodeSigningCertificateId <String>]`: key: enterpriseCodeSigningCertificate-id of enterpriseCodeSigningCertificate
  - `[IosLobAppProvisioningConfigurationAssignmentId <String>]`: key: iosLobAppProvisioningConfigurationAssignment-id of iosLobAppProvisioningConfigurationAssignment
  - `[IosLobAppProvisioningConfigurationId <String>]`: key: iosLobAppProvisioningConfiguration-id of iosLobAppProvisioningConfiguration
  - `[IosManagedAppProtectionId <String>]`: key: iosManagedAppProtection-id of iosManagedAppProtection
  - `[ManagedAppOperationId <String>]`: key: managedAppOperation-id of managedAppOperation
  - `[ManagedAppPolicyId <String>]`: key: managedAppPolicy-id of managedAppPolicy
  - `[ManagedAppRegistrationId <String>]`: key: managedAppRegistration-id of managedAppRegistration
  - `[ManagedAppStatusId <String>]`: key: managedAppStatus-id of managedAppStatus
  - `[ManagedDeviceMobileAppConfigurationAssignmentId <String>]`: key: managedDeviceMobileAppConfigurationAssignment-id of managedDeviceMobileAppConfigurationAssignment
  - `[ManagedDeviceMobileAppConfigurationDeviceStatusId <String>]`: key: managedDeviceMobileAppConfigurationDeviceStatus-id of managedDeviceMobileAppConfigurationDeviceStatus
  - `[ManagedDeviceMobileAppConfigurationId <String>]`: key: managedDeviceMobileAppConfiguration-id of managedDeviceMobileAppConfiguration
  - `[ManagedDeviceMobileAppConfigurationUserStatusId <String>]`: key: managedDeviceMobileAppConfigurationUserStatus-id of managedDeviceMobileAppConfigurationUserStatus
  - `[ManagedEBookAssignmentId <String>]`: key: managedEBookAssignment-id of managedEBookAssignment
  - `[ManagedEBookCategoryId <String>]`: key: managedEBookCategory-id of managedEBookCategory
  - `[ManagedEBookId <String>]`: key: managedEBook-id of managedEBook
  - `[ManagedMobileAppId <String>]`: key: managedMobileApp-id of managedMobileApp
  - `[MdmWindowsInformationProtectionPolicyId <String>]`: key: mdmWindowsInformationProtectionPolicy-id of mdmWindowsInformationProtectionPolicy
  - `[MobileAppAssignmentId <String>]`: key: mobileAppAssignment-id of mobileAppAssignment
  - `[MobileAppCategoryId <String>]`: key: mobileAppCategory-id of mobileAppCategory
  - `[MobileAppId <String>]`: key: mobileApp-id of mobileApp
  - `[MobileAppInstallStatusId <String>]`: key: mobileAppInstallStatus-id of mobileAppInstallStatus
  - `[MobileAppProvisioningConfigGroupAssignmentId <String>]`: key: mobileAppProvisioningConfigGroupAssignment-id of mobileAppProvisioningConfigGroupAssignment
  - `[MobileAppRelationshipId <String>]`: key: mobileAppRelationship-id of mobileAppRelationship
  - `[PolicySetAssignmentId <String>]`: key: policySetAssignment-id of policySetAssignment
  - `[PolicySetId <String>]`: key: policySet-id of policySet
  - `[PolicySetItemId <String>]`: key: policySetItem-id of policySetItem
  - `[SideLoadingKeyId <String>]`: key: sideLoadingKey-id of sideLoadingKey
  - `[Status <String>]`: 
  - `[TargetedManagedAppConfigurationId <String>]`: key: targetedManagedAppConfiguration-id of targetedManagedAppConfiguration
  - `[TargetedManagedAppPolicyAssignmentId <String>]`: key: targetedManagedAppPolicyAssignment-id of targetedManagedAppPolicyAssignment
  - `[UserAppInstallStatusId <String>]`: key: userAppInstallStatus-id of userAppInstallStatus
  - `[UserInstallStateSummaryId <String>]`: key: userInstallStateSummary-id of userInstallStateSummary
  - `[UserPrincipalName <String>]`: 
  - `[VppTokenId <String>]`: key: vppToken-id of vppToken
  - `[WindowsDefenderApplicationControlSupplementalPolicyAssignmentId <String>]`: key: windowsDefenderApplicationControlSupplementalPolicyAssignment-id of windowsDefenderApplicationControlSupplementalPolicyAssignment
  - `[WindowsDefenderApplicationControlSupplementalPolicyDeploymentStatusId <String>]`: key: windowsDefenderApplicationControlSupplementalPolicyDeploymentStatus-id of windowsDefenderApplicationControlSupplementalPolicyDeploymentStatus
  - `[WindowsDefenderApplicationControlSupplementalPolicyId <String>]`: key: windowsDefenderApplicationControlSupplementalPolicy-id of windowsDefenderApplicationControlSupplementalPolicy
  - `[WindowsInformationProtectionDeviceRegistrationId <String>]`: key: windowsInformationProtectionDeviceRegistration-id of windowsInformationProtectionDeviceRegistration
  - `[WindowsInformationProtectionPolicyId <String>]`: key: windowsInformationProtectionPolicy-id of windowsInformationProtectionPolicy
  - `[WindowsInformationProtectionWipeActionId <String>]`: key: windowsInformationProtectionWipeAction-id of windowsInformationProtectionWipeAction

## RELATED LINKS

