---
external help file:
Module Name: Microsoft.Graph.Sites.Actions
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.sites.actions/update-mgsiteonenotesectiongroupsectionpagecontent
schema: 2.0.0
---

# Update-MgSiteOnenoteSectionGroupSectionPageContent

## SYNOPSIS
Invoke action onenotePatchContent

## SYNTAX

### PatchExpanded1 (Default)
```
Update-MgSiteOnenoteSectionGroupSectionPageContent -OnenotePageId <String> -OnenoteSectionId <String>
 -SectionGroupId <String> -SiteId <String> [-Commands <IMicrosoftGraphOnenotePatchContentCommand[]>]
 [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Patch1
```
Update-MgSiteOnenoteSectionGroupSectionPageContent -OnenotePageId <String> -OnenoteSectionId <String>
 -SectionGroupId <String> -SiteId <String>
 -BodyParameter <IPaths7M7NkoSitesSiteIdOnenoteSectiongroupsSectiongroupIdSectionsOnenotesectionIdPagesOnenotepageIdMicrosoftGraphOnenotepatchcontentPostRequestbodyContentApplicationJsonSchema>
 [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### PatchViaIdentity1
```
Update-MgSiteOnenoteSectionGroupSectionPageContent -InputObject <ISitesActionsIdentity>
 -BodyParameter <IPaths7M7NkoSitesSiteIdOnenoteSectiongroupsSectiongroupIdSectionsOnenotesectionIdPagesOnenotepageIdMicrosoftGraphOnenotepatchcontentPostRequestbodyContentApplicationJsonSchema>
 [-PassThru] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### PatchViaIdentityExpanded1
```
Update-MgSiteOnenoteSectionGroupSectionPageContent -InputObject <ISitesActionsIdentity>
 [-Commands <IMicrosoftGraphOnenotePatchContentCommand[]>] [-PassThru] [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

## DESCRIPTION
Invoke action onenotePatchContent

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
.
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IPaths7M7NkoSitesSiteIdOnenoteSectiongroupsSectiongroupIdSectionsOnenotesectionIdPagesOnenotepageIdMicrosoftGraphOnenotepatchcontentPostRequestbodyContentApplicationJsonSchema
Parameter Sets: Patch1, PatchViaIdentity1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Commands
.
To construct, see NOTES section for COMMANDS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphOnenotePatchContentCommand[]
Parameter Sets: PatchExpanded1, PatchViaIdentityExpanded1
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
Type: Microsoft.Graph.PowerShell.Models.ISitesActionsIdentity
Parameter Sets: PatchViaIdentity1, PatchViaIdentityExpanded1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -OnenotePageId
key: onenotePage-id of onenotePage

```yaml
Type: System.String
Parameter Sets: Patch1, PatchExpanded1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -OnenoteSectionId
key: onenoteSection-id of onenoteSection

```yaml
Type: System.String
Parameter Sets: Patch1, PatchExpanded1
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

### -SectionGroupId
key: sectionGroup-id of sectionGroup

```yaml
Type: System.String
Parameter Sets: Patch1, PatchExpanded1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SiteId
key: site-id of site

```yaml
Type: System.String
Parameter Sets: Patch1, PatchExpanded1
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

### Microsoft.Graph.PowerShell.Models.IPaths7M7NkoSitesSiteIdOnenoteSectiongroupsSectiongroupIdSectionsOnenotesectionIdPagesOnenotepageIdMicrosoftGraphOnenotepatchcontentPostRequestbodyContentApplicationJsonSchema

### Microsoft.Graph.PowerShell.Models.ISitesActionsIdentity

## OUTPUTS

### System.Boolean

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IPaths7M7NkoSitesSiteIdOnenoteSectiongroupsSectiongroupIdSectionsOnenotesectionIdPagesOnenotepageIdMicrosoftGraphOnenotepatchcontentPostRequestbodyContentApplicationJsonSchema>: .
  - `[Commands <IMicrosoftGraphOnenotePatchContentCommand[]>]`: 
    - `[Action <String>]`: onenotePatchActionType
    - `[Content <String>]`: A string of well-formed HTML to add to the page, and any image or file binary data. If the content contains binary data, the request must be sent using the multipart/form-data content type with a 'Commands' part.
    - `[Position <String>]`: onenotePatchInsertPosition
    - `[Target <String>]`: The element to update. Must be the #<data-id> or the generated <id> of the element, or the body or title keyword.

COMMANDS <IMicrosoftGraphOnenotePatchContentCommand[]>: .
  - `[Action <String>]`: onenotePatchActionType
  - `[Content <String>]`: A string of well-formed HTML to add to the page, and any image or file binary data. If the content contains binary data, the request must be sent using the multipart/form-data content type with a 'Commands' part.
  - `[Position <String>]`: onenotePatchInsertPosition
  - `[Target <String>]`: The element to update. Must be the #<data-id> or the generated <id> of the element, or the body or title keyword.

INPUTOBJECT <ISitesActionsIdentity>: Identity Parameter
  - `[ItemActivityOldId <String>]`: key: itemActivityOLD-id of itemActivityOLD
  - `[ListId <String>]`: key: list-id of list
  - `[ListItemId <String>]`: key: listItem-id of listItem
  - `[ListItemVersionId <String>]`: key: listItemVersion-id of listItemVersion
  - `[NotebookId <String>]`: key: notebook-id of notebook
  - `[OnenotePageId <String>]`: key: onenotePage-id of onenotePage
  - `[OnenoteSectionId <String>]`: key: onenoteSection-id of onenoteSection
  - `[SectionGroupId <String>]`: key: sectionGroup-id of sectionGroup
  - `[SiteId <String>]`: key: site-id of site
  - `[SitePageId <String>]`: key: sitePage-id of sitePage

## RELATED LINKS

