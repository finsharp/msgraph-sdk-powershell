---
external help file:
Module Name: Microsoft.Graph.DevicesApps.DeviceAppManagement
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicesapps.deviceappmanagement/update-mgdeviceappmanagementmdmwindowinformationprotectionpolicy
schema: 2.0.0
---

# Update-MgDeviceAppManagementMdmWindowInformationProtectionPolicy

## SYNOPSIS
Update the navigation property mdmWindowsInformationProtectionPolicies in deviceAppManagement

## SYNTAX

### UpdateExpanded (Default)
```
Update-MgDeviceAppManagementMdmWindowInformationProtectionPolicy
 -MdmWindowsInformationProtectionPolicyId <String>
 [-Assignments <IMicrosoftGraphTargetedManagedAppPolicyAssignment1[]>] [-AzureRightsManagementServicesAllowed]
 [-CreatedDateTime <DateTime>] [-DataRecoveryCertificateCertificateInputFile <String>]
 [-DataRecoveryCertificateDescription <String>] [-DataRecoveryCertificateExpirationDateTime <DateTime>]
 [-DataRecoveryCertificateSubjectName <String>] [-Description <String>] [-DisplayName <String>]
 [-EnforcementLevel <String>] [-EnterpriseDomain <String>]
 [-EnterpriseInternalProxyServers <IMicrosoftGraphWindowsInformationProtectionResourceCollection[]>]
 [-EnterpriseIPRanges <IMicrosoftGraphWindowsInformationProtectionIPRangeCollection[]>]
 [-EnterpriseIPRangesAreAuthoritative]
 [-EnterpriseNetworkDomainNames <IMicrosoftGraphWindowsInformationProtectionResourceCollection[]>]
 [-EnterpriseProtectedDomainNames <IMicrosoftGraphWindowsInformationProtectionResourceCollection[]>]
 [-EnterpriseProxiedDomains <IMicrosoftGraphWindowsInformationProtectionProxiedDomainCollection[]>]
 [-EnterpriseProxyServers <IMicrosoftGraphWindowsInformationProtectionResourceCollection[]>]
 [-EnterpriseProxyServersAreAuthoritative]
 [-ExemptAppLockerFiles <IMicrosoftGraphWindowsInformationProtectionAppLockerFile[]>]
 [-ExemptApps <IMicrosoftGraphWindowsInformationProtectionApp[]>] [-IconsVisible] [-Id <String>]
 [-IndexingEncryptedStoresOrItemsBlocked] [-IsAssigned] [-LastModifiedDateTime <DateTime>]
 [-NeutralDomainResources <IMicrosoftGraphWindowsInformationProtectionResourceCollection[]>]
 [-ProtectedAppLockerFiles <IMicrosoftGraphWindowsInformationProtectionAppLockerFile[]>]
 [-ProtectedApps <IMicrosoftGraphWindowsInformationProtectionApp[]>] [-ProtectionUnderLockConfigRequired]
 [-RevokeOnUnenrollDisabled] [-RightsManagementServicesTemplateId <String>] [-RoleScopeTagIds <String[]>]
 [-SmbAutoEncryptedFileExtensions <IMicrosoftGraphWindowsInformationProtectionResourceCollection[]>]
 [-Version <String>] [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Update
```
Update-MgDeviceAppManagementMdmWindowInformationProtectionPolicy
 -MdmWindowsInformationProtectionPolicyId <String>
 -BodyParameter <IMicrosoftGraphMdmWindowsInformationProtectionPolicy1> [-PassThru] [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

### UpdateViaIdentity
```
Update-MgDeviceAppManagementMdmWindowInformationProtectionPolicy
 -InputObject <IDevicesAppsDeviceAppManagementIdentity>
 -BodyParameter <IMicrosoftGraphMdmWindowsInformationProtectionPolicy1> [-PassThru] [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

### UpdateViaIdentityExpanded
```
Update-MgDeviceAppManagementMdmWindowInformationProtectionPolicy
 -InputObject <IDevicesAppsDeviceAppManagementIdentity>
 [-Assignments <IMicrosoftGraphTargetedManagedAppPolicyAssignment1[]>] [-AzureRightsManagementServicesAllowed]
 [-CreatedDateTime <DateTime>] [-DataRecoveryCertificateCertificateInputFile <String>]
 [-DataRecoveryCertificateDescription <String>] [-DataRecoveryCertificateExpirationDateTime <DateTime>]
 [-DataRecoveryCertificateSubjectName <String>] [-Description <String>] [-DisplayName <String>]
 [-EnforcementLevel <String>] [-EnterpriseDomain <String>]
 [-EnterpriseInternalProxyServers <IMicrosoftGraphWindowsInformationProtectionResourceCollection[]>]
 [-EnterpriseIPRanges <IMicrosoftGraphWindowsInformationProtectionIPRangeCollection[]>]
 [-EnterpriseIPRangesAreAuthoritative]
 [-EnterpriseNetworkDomainNames <IMicrosoftGraphWindowsInformationProtectionResourceCollection[]>]
 [-EnterpriseProtectedDomainNames <IMicrosoftGraphWindowsInformationProtectionResourceCollection[]>]
 [-EnterpriseProxiedDomains <IMicrosoftGraphWindowsInformationProtectionProxiedDomainCollection[]>]
 [-EnterpriseProxyServers <IMicrosoftGraphWindowsInformationProtectionResourceCollection[]>]
 [-EnterpriseProxyServersAreAuthoritative]
 [-ExemptAppLockerFiles <IMicrosoftGraphWindowsInformationProtectionAppLockerFile[]>]
 [-ExemptApps <IMicrosoftGraphWindowsInformationProtectionApp[]>] [-IconsVisible] [-Id <String>]
 [-IndexingEncryptedStoresOrItemsBlocked] [-IsAssigned] [-LastModifiedDateTime <DateTime>]
 [-NeutralDomainResources <IMicrosoftGraphWindowsInformationProtectionResourceCollection[]>]
 [-ProtectedAppLockerFiles <IMicrosoftGraphWindowsInformationProtectionAppLockerFile[]>]
 [-ProtectedApps <IMicrosoftGraphWindowsInformationProtectionApp[]>] [-ProtectionUnderLockConfigRequired]
 [-RevokeOnUnenrollDisabled] [-RightsManagementServicesTemplateId <String>] [-RoleScopeTagIds <String[]>]
 [-SmbAutoEncryptedFileExtensions <IMicrosoftGraphWindowsInformationProtectionResourceCollection[]>]
 [-Version <String>] [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
Update the navigation property mdmWindowsInformationProtectionPolicies in deviceAppManagement

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
Navigation property to list of security groups targeted for policy.
To construct, see NOTES section for ASSIGNMENTS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphTargetedManagedAppPolicyAssignment1[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AzureRightsManagementServicesAllowed
Specifies whether to allow Azure RMS encryption for WIP

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
Policy for Windows information protection with MDM
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphMdmWindowsInformationProtectionPolicy1
Parameter Sets: Update, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -CreatedDateTime
The date and time the policy was created.

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

### -DataRecoveryCertificateCertificateInputFile
Input File for DataRecoveryCertificateCertificate (Data recovery Certificate)

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

### -DataRecoveryCertificateDescription
Data recovery Certificate description

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

### -DataRecoveryCertificateExpirationDateTime
Data recovery Certificate expiration datetime

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

### -DataRecoveryCertificateSubjectName
Data recovery Certificate subject name

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

### -Description
The policy's description.

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

### -DisplayName
Policy display name.

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

### -EnforcementLevel
windowsInformationProtectionEnforcementLevel

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

### -EnterpriseDomain
Primary enterprise domain

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

### -EnterpriseInternalProxyServers
This is the comma-separated list of internal proxy servers.
For example, '157.54.14.28, 157.54.11.118, 10.202.14.167, 157.53.14.163, 157.69.210.59'.
These proxies have been configured by the admin to connect to specific resources on the Internet.
They are considered to be enterprise network locations.
The proxies are only leveraged in configuring the EnterpriseProxiedDomains policy to force traffic to the matched domains through these proxies
To construct, see NOTES section for ENTERPRISEINTERNALPROXYSERVERS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphWindowsInformationProtectionResourceCollection[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EnterpriseIPRanges
Sets the enterprise IP ranges that define the computers in the enterprise network.
Data that comes from those computers will be considered part of the enterprise and protected.
These locations will be considered a safe destination for enterprise data to be shared to
To construct, see NOTES section for ENTERPRISEIPRANGES properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphWindowsInformationProtectionIPRangeCollection[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EnterpriseIPRangesAreAuthoritative
Boolean value that tells the client to accept the configured list and not to use heuristics to attempt to find other subnets.
Default is false

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EnterpriseNetworkDomainNames
This is the list of domains that comprise the boundaries of the enterprise.
Data from one of these domains that is sent to a device will be considered enterprise data and protected These locations will be considered a safe destination for enterprise data to be shared to
To construct, see NOTES section for ENTERPRISENETWORKDOMAINNAMES properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphWindowsInformationProtectionResourceCollection[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EnterpriseProtectedDomainNames
List of enterprise domains to be protected
To construct, see NOTES section for ENTERPRISEPROTECTEDDOMAINNAMES properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphWindowsInformationProtectionResourceCollection[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EnterpriseProxiedDomains
Contains a list of Enterprise resource domains hosted in the cloud that need to be protected.
Connections to these resources are considered enterprise data.
If a proxy is paired with a cloud resource, traffic to the cloud resource will be routed through the enterprise network via the denoted proxy server (on Port 80).
A proxy server used for this purpose must also be configured using the EnterpriseInternalProxyServers policy
To construct, see NOTES section for ENTERPRISEPROXIEDDOMAINS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphWindowsInformationProtectionProxiedDomainCollection[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EnterpriseProxyServers
This is a list of proxy servers.
Any server not on this list is considered non-enterprise
To construct, see NOTES section for ENTERPRISEPROXYSERVERS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphWindowsInformationProtectionResourceCollection[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EnterpriseProxyServersAreAuthoritative
Boolean value that tells the client to accept the configured list of proxies and not try to detect other work proxies.
Default is false

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ExemptAppLockerFiles
Another way to input exempt apps through xml files
To construct, see NOTES section for EXEMPTAPPLOCKERFILES properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphWindowsInformationProtectionAppLockerFile[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ExemptApps
Exempt applications can also access enterprise data, but the data handled by those applications are not protected.
This is because some critical enterprise applications may have compatibility problems with encrypted data.
To construct, see NOTES section for EXEMPTAPPS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphWindowsInformationProtectionApp[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IconsVisible
Determines whether overlays are added to icons for WIP protected files in Explorer and enterprise only app tiles in the Start menu.
Starting in Windows 10, version 1703 this setting also configures the visibility of the WIP icon in the title bar of a WIP-protected app

```yaml
Type: System.Management.Automation.SwitchParameter
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

### -IndexingEncryptedStoresOrItemsBlocked
This switch is for the Windows Search Indexer, to allow or disallow indexing of items

```yaml
Type: System.Management.Automation.SwitchParameter
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

### -IsAssigned
Indicates if the policy is deployed to any inclusion groups or not.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -LastModifiedDateTime
Last time the policy was modified.

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

### -MdmWindowsInformationProtectionPolicyId
key: mdmWindowsInformationProtectionPolicy-id of mdmWindowsInformationProtectionPolicy

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

### -NeutralDomainResources
List of domain names that can used for work or personal resource
To construct, see NOTES section for NEUTRALDOMAINRESOURCES properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphWindowsInformationProtectionResourceCollection[]
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

### -ProtectedAppLockerFiles
Another way to input protected apps through xml files
To construct, see NOTES section for PROTECTEDAPPLOCKERFILES properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphWindowsInformationProtectionAppLockerFile[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ProtectedApps
Protected applications can access enterprise data and the data handled by those applications are protected with encryption
To construct, see NOTES section for PROTECTEDAPPS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphWindowsInformationProtectionApp[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ProtectionUnderLockConfigRequired
Specifies whether the protection under lock feature (also known as encrypt under pin) should be configured

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RevokeOnUnenrollDisabled
This policy controls whether to revoke the WIP keys when a device unenrolls from the management service.
If set to 1 (Don't revoke keys), the keys will not be revoked and the user will continue to have access to protected files after unenrollment.
If the keys are not revoked, there will be no revoked file cleanup subsequently.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RightsManagementServicesTemplateId
TemplateID GUID to use for RMS encryption.
The RMS template allows the IT admin to configure the details about who has access to RMS-protected file and how long they have access

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

### -RoleScopeTagIds
List of Scope Tags for this Entity instance.

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

### -SmbAutoEncryptedFileExtensions
Specifies a list of file extensions, so that files with these extensions are encrypted when copying from an SMB share within the corporate boundary
To construct, see NOTES section for SMBAUTOENCRYPTEDFILEEXTENSIONS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphWindowsInformationProtectionResourceCollection[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Version
Version of the entity.

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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphMdmWindowsInformationProtectionPolicy1

## OUTPUTS

### System.Boolean

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


ASSIGNMENTS <IMicrosoftGraphTargetedManagedAppPolicyAssignment1[]>: Navigation property to list of security groups targeted for policy.
  - `[Id <String>]`: Read-only.
  - `[Source <String>]`: deviceAndAppManagementAssignmentSource
  - `[SourceId <String>]`: Identifier for resource used for deployment to a group
  - `[Target <IMicrosoftGraphDeviceAndAppManagementAssignmentTarget>]`: deviceAndAppManagementAssignmentTarget

BODYPARAMETER <IMicrosoftGraphMdmWindowsInformationProtectionPolicy1>: Policy for Windows information protection with MDM
  - `[Assignments <IMicrosoftGraphTargetedManagedAppPolicyAssignment1[]>]`: Navigation property to list of security groups targeted for policy.
    - `[Id <String>]`: Read-only.
    - `[Source <String>]`: deviceAndAppManagementAssignmentSource
    - `[SourceId <String>]`: Identifier for resource used for deployment to a group
    - `[Target <IMicrosoftGraphDeviceAndAppManagementAssignmentTarget>]`: deviceAndAppManagementAssignmentTarget
  - `[AzureRightsManagementServicesAllowed <Boolean?>]`: Specifies whether to allow Azure RMS encryption for WIP
  - `[DataRecoveryCertificateCertificate <Byte[]>]`: Data recovery Certificate
  - `[DataRecoveryCertificateDescription <String>]`: Data recovery Certificate description
  - `[DataRecoveryCertificateExpirationDateTime <DateTime?>]`: Data recovery Certificate expiration datetime
  - `[DataRecoveryCertificateSubjectName <String>]`: Data recovery Certificate subject name
  - `[EnforcementLevel <String>]`: windowsInformationProtectionEnforcementLevel
  - `[EnterpriseDomain <String>]`: Primary enterprise domain
  - `[EnterpriseIPRanges <IMicrosoftGraphWindowsInformationProtectionIPRangeCollection[]>]`: Sets the enterprise IP ranges that define the computers in the enterprise network. Data that comes from those computers will be considered part of the enterprise and protected. These locations will be considered a safe destination for enterprise data to be shared to
    - `[DisplayName <String>]`: Display name
    - `[Ranges <IMicrosoftGraphIPRange[]>]`: Collection of Internet protocol address ranges
  - `[EnterpriseIPRangesAreAuthoritative <Boolean?>]`: Boolean value that tells the client to accept the configured list and not to use heuristics to attempt to find other subnets. Default is false
  - `[EnterpriseInternalProxyServers <IMicrosoftGraphWindowsInformationProtectionResourceCollection[]>]`: This is the comma-separated list of internal proxy servers. For example, '157.54.14.28, 157.54.11.118, 10.202.14.167, 157.53.14.163, 157.69.210.59'. These proxies have been configured by the admin to connect to specific resources on the Internet. They are considered to be enterprise network locations. The proxies are only leveraged in configuring the EnterpriseProxiedDomains policy to force traffic to the matched domains through these proxies
    - `[DisplayName <String>]`: Display name
    - `[Resources <String[]>]`: Collection of resources
  - `[EnterpriseNetworkDomainNames <IMicrosoftGraphWindowsInformationProtectionResourceCollection[]>]`: This is the list of domains that comprise the boundaries of the enterprise. Data from one of these domains that is sent to a device will be considered enterprise data and protected These locations will be considered a safe destination for enterprise data to be shared to
  - `[EnterpriseProtectedDomainNames <IMicrosoftGraphWindowsInformationProtectionResourceCollection[]>]`: List of enterprise domains to be protected
  - `[EnterpriseProxiedDomains <IMicrosoftGraphWindowsInformationProtectionProxiedDomainCollection[]>]`: Contains a list of Enterprise resource domains hosted in the cloud that need to be protected. Connections to these resources are considered enterprise data. If a proxy is paired with a cloud resource, traffic to the cloud resource will be routed through the enterprise network via the denoted proxy server (on Port 80). A proxy server used for this purpose must also be configured using the EnterpriseInternalProxyServers policy
    - `[DisplayName <String>]`: Display name
    - `[ProxiedDomains <IMicrosoftGraphProxiedDomain[]>]`: Collection of proxied domains
      - `[IPAddressOrFqdn <String>]`: The IP address or FQDN
      - `[Proxy <String>]`: Proxy IP or FQDN
  - `[EnterpriseProxyServers <IMicrosoftGraphWindowsInformationProtectionResourceCollection[]>]`: This is a list of proxy servers. Any server not on this list is considered non-enterprise
  - `[EnterpriseProxyServersAreAuthoritative <Boolean?>]`: Boolean value that tells the client to accept the configured list of proxies and not try to detect other work proxies. Default is false
  - `[ExemptAppLockerFiles <IMicrosoftGraphWindowsInformationProtectionAppLockerFile[]>]`: Another way to input exempt apps through xml files
    - `[Id <String>]`: Read-only.
    - `[DisplayName <String>]`: The friendly name
    - `[File <Byte[]>]`: File as a byte array
    - `[FileHash <String>]`: SHA256 hash of the file
    - `[Version <String>]`: Version of the entity.
  - `[ExemptApps <IMicrosoftGraphWindowsInformationProtectionApp[]>]`: Exempt applications can also access enterprise data, but the data handled by those applications are not protected. This is because some critical enterprise applications may have compatibility problems with encrypted data.
    - `[Denied <Boolean?>]`: If true, app is denied protection or exemption.
    - `[Description <String>]`: The app's description.
    - `[DisplayName <String>]`: App display name.
    - `[ProductName <String>]`: The product name.
    - `[PublisherName <String>]`: The publisher name
  - `[IconsVisible <Boolean?>]`: Determines whether overlays are added to icons for WIP protected files in Explorer and enterprise only app tiles in the Start menu. Starting in Windows 10, version 1703 this setting also configures the visibility of the WIP icon in the title bar of a WIP-protected app
  - `[IndexingEncryptedStoresOrItemsBlocked <Boolean?>]`: This switch is for the Windows Search Indexer, to allow or disallow indexing of items
  - `[IsAssigned <Boolean?>]`: Indicates if the policy is deployed to any inclusion groups or not.
  - `[NeutralDomainResources <IMicrosoftGraphWindowsInformationProtectionResourceCollection[]>]`: List of domain names that can used for work or personal resource
  - `[ProtectedAppLockerFiles <IMicrosoftGraphWindowsInformationProtectionAppLockerFile[]>]`: Another way to input protected apps through xml files
  - `[ProtectedApps <IMicrosoftGraphWindowsInformationProtectionApp[]>]`: Protected applications can access enterprise data and the data handled by those applications are protected with encryption
  - `[ProtectionUnderLockConfigRequired <Boolean?>]`: Specifies whether the protection under lock feature (also known as encrypt under pin) should be configured
  - `[RevokeOnUnenrollDisabled <Boolean?>]`: This policy controls whether to revoke the WIP keys when a device unenrolls from the management service. If set to 1 (Don't revoke keys), the keys will not be revoked and the user will continue to have access to protected files after unenrollment. If the keys are not revoked, there will be no revoked file cleanup subsequently.
  - `[RightsManagementServicesTemplateId <String>]`: TemplateID GUID to use for RMS encryption. The RMS template allows the IT admin to configure the details about who has access to RMS-protected file and how long they have access
  - `[SmbAutoEncryptedFileExtensions <IMicrosoftGraphWindowsInformationProtectionResourceCollection[]>]`: Specifies a list of file extensions, so that files with these extensions are encrypted when copying from an SMB share within the corporate boundary
  - `[CreatedDateTime <DateTime?>]`: The date and time the policy was created.
  - `[Description <String>]`: The policy's description.
  - `[DisplayName <String>]`: Policy display name.
  - `[LastModifiedDateTime <DateTime?>]`: Last time the policy was modified.
  - `[RoleScopeTagIds <String[]>]`: List of Scope Tags for this Entity instance.
  - `[Version <String>]`: Version of the entity.
  - `[Id <String>]`: Read-only.

ENTERPRISEINTERNALPROXYSERVERS <IMicrosoftGraphWindowsInformationProtectionResourceCollection[]>: This is the comma-separated list of internal proxy servers. For example, '157.54.14.28, 157.54.11.118, 10.202.14.167, 157.53.14.163, 157.69.210.59'. These proxies have been configured by the admin to connect to specific resources on the Internet. They are considered to be enterprise network locations. The proxies are only leveraged in configuring the EnterpriseProxiedDomains policy to force traffic to the matched domains through these proxies
  - `[DisplayName <String>]`: Display name
  - `[Resources <String[]>]`: Collection of resources

ENTERPRISEIPRANGES <IMicrosoftGraphWindowsInformationProtectionIPRangeCollection[]>: Sets the enterprise IP ranges that define the computers in the enterprise network. Data that comes from those computers will be considered part of the enterprise and protected. These locations will be considered a safe destination for enterprise data to be shared to
  - `[DisplayName <String>]`: Display name
  - `[Ranges <IMicrosoftGraphIPRange[]>]`: Collection of Internet protocol address ranges

ENTERPRISENETWORKDOMAINNAMES <IMicrosoftGraphWindowsInformationProtectionResourceCollection[]>: This is the list of domains that comprise the boundaries of the enterprise. Data from one of these domains that is sent to a device will be considered enterprise data and protected These locations will be considered a safe destination for enterprise data to be shared to
  - `[DisplayName <String>]`: Display name
  - `[Resources <String[]>]`: Collection of resources

ENTERPRISEPROTECTEDDOMAINNAMES <IMicrosoftGraphWindowsInformationProtectionResourceCollection[]>: List of enterprise domains to be protected
  - `[DisplayName <String>]`: Display name
  - `[Resources <String[]>]`: Collection of resources

ENTERPRISEPROXIEDDOMAINS <IMicrosoftGraphWindowsInformationProtectionProxiedDomainCollection[]>: Contains a list of Enterprise resource domains hosted in the cloud that need to be protected. Connections to these resources are considered enterprise data. If a proxy is paired with a cloud resource, traffic to the cloud resource will be routed through the enterprise network via the denoted proxy server (on Port 80). A proxy server used for this purpose must also be configured using the EnterpriseInternalProxyServers policy
  - `[DisplayName <String>]`: Display name
  - `[ProxiedDomains <IMicrosoftGraphProxiedDomain[]>]`: Collection of proxied domains
    - `[IPAddressOrFqdn <String>]`: The IP address or FQDN
    - `[Proxy <String>]`: Proxy IP or FQDN

ENTERPRISEPROXYSERVERS <IMicrosoftGraphWindowsInformationProtectionResourceCollection[]>: This is a list of proxy servers. Any server not on this list is considered non-enterprise
  - `[DisplayName <String>]`: Display name
  - `[Resources <String[]>]`: Collection of resources

EXEMPTAPPLOCKERFILES <IMicrosoftGraphWindowsInformationProtectionAppLockerFile[]>: Another way to input exempt apps through xml files
  - `[Id <String>]`: Read-only.
  - `[DisplayName <String>]`: The friendly name
  - `[File <Byte[]>]`: File as a byte array
  - `[FileHash <String>]`: SHA256 hash of the file
  - `[Version <String>]`: Version of the entity.

EXEMPTAPPS <IMicrosoftGraphWindowsInformationProtectionApp[]>: Exempt applications can also access enterprise data, but the data handled by those applications are not protected. This is because some critical enterprise applications may have compatibility problems with encrypted data.
  - `[Denied <Boolean?>]`: If true, app is denied protection or exemption.
  - `[Description <String>]`: The app's description.
  - `[DisplayName <String>]`: App display name.
  - `[ProductName <String>]`: The product name.
  - `[PublisherName <String>]`: The publisher name

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

NEUTRALDOMAINRESOURCES <IMicrosoftGraphWindowsInformationProtectionResourceCollection[]>: List of domain names that can used for work or personal resource
  - `[DisplayName <String>]`: Display name
  - `[Resources <String[]>]`: Collection of resources

PROTECTEDAPPLOCKERFILES <IMicrosoftGraphWindowsInformationProtectionAppLockerFile[]>: Another way to input protected apps through xml files
  - `[Id <String>]`: Read-only.
  - `[DisplayName <String>]`: The friendly name
  - `[File <Byte[]>]`: File as a byte array
  - `[FileHash <String>]`: SHA256 hash of the file
  - `[Version <String>]`: Version of the entity.

PROTECTEDAPPS <IMicrosoftGraphWindowsInformationProtectionApp[]>: Protected applications can access enterprise data and the data handled by those applications are protected with encryption
  - `[Denied <Boolean?>]`: If true, app is denied protection or exemption.
  - `[Description <String>]`: The app's description.
  - `[DisplayName <String>]`: App display name.
  - `[ProductName <String>]`: The product name.
  - `[PublisherName <String>]`: The publisher name

SMBAUTOENCRYPTEDFILEEXTENSIONS <IMicrosoftGraphWindowsInformationProtectionResourceCollection[]>: Specifies a list of file extensions, so that files with these extensions are encrypted when copying from an SMB share within the corporate boundary
  - `[DisplayName <String>]`: Display name
  - `[Resources <String[]>]`: Collection of resources

## RELATED LINKS

