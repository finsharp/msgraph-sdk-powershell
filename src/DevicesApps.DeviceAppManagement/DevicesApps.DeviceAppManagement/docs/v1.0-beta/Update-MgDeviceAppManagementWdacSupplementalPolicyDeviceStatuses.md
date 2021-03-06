---
external help file:
Module Name: Microsoft.Graph.DevicesApps.DeviceAppManagement
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicesapps.deviceappmanagement/update-mgdeviceappmanagementwdacsupplementalpolicydevicestatuses
schema: 2.0.0
---

# Update-MgDeviceAppManagementWdacSupplementalPolicyDeviceStatuses

## SYNOPSIS
Update the navigation property deviceStatuses in deviceAppManagement

## SYNTAX

### UpdateExpanded (Default)
```
Update-MgDeviceAppManagementWdacSupplementalPolicyDeviceStatuses
 -WindowsDefenderApplicationControlSupplementalPolicyDeploymentStatusId <String>
 -WindowsDefenderApplicationControlSupplementalPolicyId <String> [-DeploymentStatus <String>]
 [-DeploySummaryDeployedDeviceCount <Int32>] [-DeploySummaryFailedDeviceCount <Int32>]
 [-DeploySummaryId <String>] [-DeviceId <String>] [-DeviceName <String>] [-Id <String>]
 [-LastSyncDateTime <DateTime>] [-OSDescription <String>] [-OSVersion <String>]
 [-PolicyAssignments <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyAssignment[]>]
 [-PolicyContentFileName <String>] [-PolicyContentInputFile <String>] [-PolicyCreationDateTime <DateTime>]
 [-PolicyDescription <String>]
 [-PolicyDeviceStatuses <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyDeploymentStatus[]>]
 [-PolicyDisplayName <String>] [-PolicyId <String>] [-PolicyLastModifiedDateTime <DateTime>]
 [-PolicyRoleScopeTagIds <String[]>] [-PolicyVersion <String>] [-UserName <String>]
 [-UserPrincipalName <String>] [-Version <String>] [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Update
```
Update-MgDeviceAppManagementWdacSupplementalPolicyDeviceStatuses
 -WindowsDefenderApplicationControlSupplementalPolicyDeploymentStatusId <String>
 -WindowsDefenderApplicationControlSupplementalPolicyId <String>
 -BodyParameter <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyDeploymentStatus>
 [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### UpdateViaIdentity
```
Update-MgDeviceAppManagementWdacSupplementalPolicyDeviceStatuses
 -InputObject <IDevicesAppsDeviceAppManagementIdentity>
 -BodyParameter <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyDeploymentStatus>
 [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### UpdateViaIdentityExpanded
```
Update-MgDeviceAppManagementWdacSupplementalPolicyDeviceStatuses
 -InputObject <IDevicesAppsDeviceAppManagementIdentity> [-DeploymentStatus <String>]
 [-DeploySummaryDeployedDeviceCount <Int32>] [-DeploySummaryFailedDeviceCount <Int32>]
 [-DeploySummaryId <String>] [-DeviceId <String>] [-DeviceName <String>] [-Id <String>]
 [-LastSyncDateTime <DateTime>] [-OSDescription <String>] [-OSVersion <String>]
 [-PolicyAssignments <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyAssignment[]>]
 [-PolicyContentFileName <String>] [-PolicyContentInputFile <String>] [-PolicyCreationDateTime <DateTime>]
 [-PolicyDescription <String>]
 [-PolicyDeviceStatuses <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyDeploymentStatus[]>]
 [-PolicyDisplayName <String>] [-PolicyId <String>] [-PolicyLastModifiedDateTime <DateTime>]
 [-PolicyRoleScopeTagIds <String[]>] [-PolicyVersion <String>] [-UserName <String>]
 [-UserPrincipalName <String>] [-Version <String>] [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
Update the navigation property deviceStatuses in deviceAppManagement

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
Contains properties for the deployment state of a WindowsDefenderApplicationControl supplemental policy for a device.
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyDeploymentStatus
Parameter Sets: Update, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -DeploymentStatus
windowsDefenderApplicationControlSupplementalPolicyStatuses

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

### -DeploySummaryDeployedDeviceCount
Number of Devices that have successfully deployed this WindowsDefenderApplicationControl supplemental policy.

```yaml
Type: System.Int32
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DeploySummaryFailedDeviceCount
Number of Devices that have failed to deploy this WindowsDefenderApplicationControl supplemental policy.

```yaml
Type: System.Int32
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DeploySummaryId
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

### -DeviceId
Device ID.

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

### -DeviceName
Device name.

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
Type: Microsoft.Graph.PowerShell.Models.IDevicesAppsDeviceAppManagementIdentity
Parameter Sets: UpdateViaIdentity, UpdateViaIdentityExpanded
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -LastSyncDateTime
Last sync date time.

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

### -OSDescription
Windows OS Version Description.

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

### -OSVersion
Windows OS Version.

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

### -PolicyAssignments
The associated group assignments for this WindowsDefenderApplicationControl supplemental policy.
To construct, see NOTES section for POLICYASSIGNMENTS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyAssignment[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PolicyContentFileName
The WindowsDefenderApplicationControl supplemental policy content's file name.

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

### -PolicyContentInputFile
Input File for PolicyContent (The WindowsDefenderApplicationControl supplemental policy content in byte array format.)

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

### -PolicyCreationDateTime
The date and time when the WindowsDefenderApplicationControl supplemental policy was uploaded.

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

### -PolicyDescription
The description of WindowsDefenderApplicationControl supplemental policy.

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

### -PolicyDeviceStatuses
The list of device deployment states for this WindowsDefenderApplicationControl supplemental policy.
To construct, see NOTES section for POLICYDEVICESTATUSES properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyDeploymentStatus[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PolicyDisplayName
The display name of WindowsDefenderApplicationControl supplemental policy.

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

### -PolicyId
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

### -PolicyLastModifiedDateTime
The date and time when the WindowsDefenderApplicationControl supplemental policy was last modified.

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

### -PolicyRoleScopeTagIds
List of Scope Tags for this WindowsDefenderApplicationControl supplemental policy entity.

```yaml
Type: System.String[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PolicyVersion
Human readable version of the WindowsDefenderApplicationControl supplemental policy.

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

### -UserName
The name of the user of this device.

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

### -UserPrincipalName
User Principal Name.

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

### -Version
The WindowsDefenderApplicationControl supplemental policy's version.

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

### -WindowsDefenderApplicationControlSupplementalPolicyDeploymentStatusId
key: windowsDefenderApplicationControlSupplementalPolicyDeploymentStatus-id of windowsDefenderApplicationControlSupplementalPolicyDeploymentStatus

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

### -WindowsDefenderApplicationControlSupplementalPolicyId
key: windowsDefenderApplicationControlSupplementalPolicy-id of windowsDefenderApplicationControlSupplementalPolicy

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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyDeploymentStatus

## OUTPUTS

### System.Boolean

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyDeploymentStatus>: Contains properties for the deployment state of a WindowsDefenderApplicationControl supplemental policy for a device.
  - `[Id <String>]`: Read-only.
  - `[DeploySummaryDeployedDeviceCount <Int32?>]`: Number of Devices that have successfully deployed this WindowsDefenderApplicationControl supplemental policy.
  - `[DeploySummaryFailedDeviceCount <Int32?>]`: Number of Devices that have failed to deploy this WindowsDefenderApplicationControl supplemental policy.
  - `[DeploySummaryId <String>]`: Read-only.
  - `[DeploymentStatus <String>]`: windowsDefenderApplicationControlSupplementalPolicyStatuses
  - `[DeviceId <String>]`: Device ID.
  - `[DeviceName <String>]`: Device name.
  - `[LastSyncDateTime <DateTime?>]`: Last sync date time.
  - `[OSDescription <String>]`: Windows OS Version Description.
  - `[OSVersion <String>]`: Windows OS Version.
  - `[PolicyAssignments <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyAssignment[]>]`: The associated group assignments for this WindowsDefenderApplicationControl supplemental policy.
    - `[Id <String>]`: Read-only.
    - `[Target <IMicrosoftGraphDeviceAndAppManagementAssignmentTarget>]`: deviceAndAppManagementAssignmentTarget
  - `[PolicyContent <Byte[]>]`: The WindowsDefenderApplicationControl supplemental policy content in byte array format.
  - `[PolicyContentFileName <String>]`: The WindowsDefenderApplicationControl supplemental policy content's file name.
  - `[PolicyCreationDateTime <DateTime?>]`: The date and time when the WindowsDefenderApplicationControl supplemental policy was uploaded.
  - `[PolicyDescription <String>]`: The description of WindowsDefenderApplicationControl supplemental policy.
  - `[PolicyDeviceStatuses <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyDeploymentStatus[]>]`: The list of device deployment states for this WindowsDefenderApplicationControl supplemental policy.
  - `[PolicyDisplayName <String>]`: The display name of WindowsDefenderApplicationControl supplemental policy.
  - `[PolicyId <String>]`: Read-only.
  - `[PolicyLastModifiedDateTime <DateTime?>]`: The date and time when the WindowsDefenderApplicationControl supplemental policy was last modified.
  - `[PolicyRoleScopeTagIds <String[]>]`: List of Scope Tags for this WindowsDefenderApplicationControl supplemental policy entity.
  - `[PolicyVersion <String>]`: Human readable version of the WindowsDefenderApplicationControl supplemental policy.
  - `[UserName <String>]`: The name of the user of this device.
  - `[UserPrincipalName <String>]`: User Principal Name.
  - `[Version <String>]`: The WindowsDefenderApplicationControl supplemental policy's version.

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

POLICYASSIGNMENTS <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyAssignment[]>: The associated group assignments for this WindowsDefenderApplicationControl supplemental policy.
  - `[Id <String>]`: Read-only.
  - `[Target <IMicrosoftGraphDeviceAndAppManagementAssignmentTarget>]`: deviceAndAppManagementAssignmentTarget

POLICYDEVICESTATUSES <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyDeploymentStatus[]>: The list of device deployment states for this WindowsDefenderApplicationControl supplemental policy.
  - `[Id <String>]`: Read-only.
  - `[DeploySummaryDeployedDeviceCount <Int32?>]`: Number of Devices that have successfully deployed this WindowsDefenderApplicationControl supplemental policy.
  - `[DeploySummaryFailedDeviceCount <Int32?>]`: Number of Devices that have failed to deploy this WindowsDefenderApplicationControl supplemental policy.
  - `[DeploySummaryId <String>]`: Read-only.
  - `[DeploymentStatus <String>]`: windowsDefenderApplicationControlSupplementalPolicyStatuses
  - `[DeviceId <String>]`: Device ID.
  - `[DeviceName <String>]`: Device name.
  - `[LastSyncDateTime <DateTime?>]`: Last sync date time.
  - `[OSDescription <String>]`: Windows OS Version Description.
  - `[OSVersion <String>]`: Windows OS Version.
  - `[PolicyAssignments <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyAssignment[]>]`: The associated group assignments for this WindowsDefenderApplicationControl supplemental policy.
    - `[Id <String>]`: Read-only.
    - `[Target <IMicrosoftGraphDeviceAndAppManagementAssignmentTarget>]`: deviceAndAppManagementAssignmentTarget
  - `[PolicyContent <Byte[]>]`: The WindowsDefenderApplicationControl supplemental policy content in byte array format.
  - `[PolicyContentFileName <String>]`: The WindowsDefenderApplicationControl supplemental policy content's file name.
  - `[PolicyCreationDateTime <DateTime?>]`: The date and time when the WindowsDefenderApplicationControl supplemental policy was uploaded.
  - `[PolicyDescription <String>]`: The description of WindowsDefenderApplicationControl supplemental policy.
  - `[PolicyDeviceStatuses <IMicrosoftGraphWindowsDefenderApplicationControlSupplementalPolicyDeploymentStatus[]>]`: The list of device deployment states for this WindowsDefenderApplicationControl supplemental policy.
  - `[PolicyDisplayName <String>]`: The display name of WindowsDefenderApplicationControl supplemental policy.
  - `[PolicyId <String>]`: Read-only.
  - `[PolicyLastModifiedDateTime <DateTime?>]`: The date and time when the WindowsDefenderApplicationControl supplemental policy was last modified.
  - `[PolicyRoleScopeTagIds <String[]>]`: List of Scope Tags for this WindowsDefenderApplicationControl supplemental policy entity.
  - `[PolicyVersion <String>]`: Human readable version of the WindowsDefenderApplicationControl supplemental policy.
  - `[UserName <String>]`: The name of the user of this device.
  - `[UserPrincipalName <String>]`: User Principal Name.
  - `[Version <String>]`: The WindowsDefenderApplicationControl supplemental policy's version.

## RELATED LINKS

