---
external help file:
Module Name: Microsoft.Graph.Users.Mail
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.users.mail/new-mgusermessage
schema: 2.0.0
---

# New-MgUserMessage

## SYNOPSIS
Create new navigation property to messages for users

## SYNTAX

### CreateExpanded1 (Default)
```
New-MgUserMessage -UserId <String> [-Attachments <IMicrosoftGraphAttachment[]>]
 [-BccRecipients <IMicrosoftGraphRecipient[]>] [-BodyContent <String>] [-BodyContentType <String>]
 [-BodyPreview <String>] [-Categories <String[]>] [-CcRecipients <IMicrosoftGraphRecipient[]>]
 [-ChangeKey <String>] [-CompletedDateTime <String>] [-CompletedDateTimeZone <String>]
 [-ConversationId <String>] [-ConversationIndexInputFile <String>] [-CreatedDateTime <DateTime>]
 [-DueDateTime <String>] [-DueDateTimeZone <String>] [-Extensions <IMicrosoftGraphExtension[]>]
 [-FlagStatus <String>] [-From <IMicrosoftGraphRecipient>] [-HasAttachments] [-Id <String>]
 [-Importance <String>] [-InferenceClassification <String>]
 [-InternetMessageHeaders <IMicrosoftGraphInternetMessageHeader[]>] [-InternetMessageId <String>]
 [-IsDeliveryReceiptRequested] [-IsDraft] [-IsRead] [-IsReadReceiptRequested]
 [-LastModifiedDateTime <DateTime>] [-MentionPreviewIsMentioned] [-Mentions <IMicrosoftGraphMention[]>]
 [-MultiValueExtendedProperties <IMicrosoftGraphMultiValueLegacyExtendedProperty[]>]
 [-ParentFolderId <String>] [-ReceivedDateTime <DateTime>] [-ReplyTo <IMicrosoftGraphRecipient[]>]
 [-Sender <IMicrosoftGraphRecipient>] [-SentDateTime <DateTime>]
 [-SingleValueExtendedProperties <IMicrosoftGraphSingleValueLegacyExtendedProperty[]>]
 [-StartDateTime <String>] [-StartDateTimeZone <String>] [-Subject <String>]
 [-ToRecipients <IMicrosoftGraphRecipient[]>] [-UniqueBodyContent <String>] [-UniqueBodyContentType <String>]
 [-UnsubscribeData <String[]>] [-UnsubscribeEnabled] [-WebLink <String>] [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

### Create1
```
New-MgUserMessage -UserId <String> -BodyParameter <IMicrosoftGraphMessage1> [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

### CreateViaIdentity1
```
New-MgUserMessage -InputObject <IUsersMailIdentity> -BodyParameter <IMicrosoftGraphMessage1> [-Confirm]
 [-WhatIf] [<CommonParameters>]
```

### CreateViaIdentityExpanded1
```
New-MgUserMessage -InputObject <IUsersMailIdentity> [-Attachments <IMicrosoftGraphAttachment[]>]
 [-BccRecipients <IMicrosoftGraphRecipient[]>] [-BodyContent <String>] [-BodyContentType <String>]
 [-BodyPreview <String>] [-Categories <String[]>] [-CcRecipients <IMicrosoftGraphRecipient[]>]
 [-ChangeKey <String>] [-CompletedDateTime <String>] [-CompletedDateTimeZone <String>]
 [-ConversationId <String>] [-ConversationIndexInputFile <String>] [-CreatedDateTime <DateTime>]
 [-DueDateTime <String>] [-DueDateTimeZone <String>] [-Extensions <IMicrosoftGraphExtension[]>]
 [-FlagStatus <String>] [-From <IMicrosoftGraphRecipient>] [-HasAttachments] [-Id <String>]
 [-Importance <String>] [-InferenceClassification <String>]
 [-InternetMessageHeaders <IMicrosoftGraphInternetMessageHeader[]>] [-InternetMessageId <String>]
 [-IsDeliveryReceiptRequested] [-IsDraft] [-IsRead] [-IsReadReceiptRequested]
 [-LastModifiedDateTime <DateTime>] [-MentionPreviewIsMentioned] [-Mentions <IMicrosoftGraphMention[]>]
 [-MultiValueExtendedProperties <IMicrosoftGraphMultiValueLegacyExtendedProperty[]>]
 [-ParentFolderId <String>] [-ReceivedDateTime <DateTime>] [-ReplyTo <IMicrosoftGraphRecipient[]>]
 [-Sender <IMicrosoftGraphRecipient>] [-SentDateTime <DateTime>]
 [-SingleValueExtendedProperties <IMicrosoftGraphSingleValueLegacyExtendedProperty[]>]
 [-StartDateTime <String>] [-StartDateTimeZone <String>] [-Subject <String>]
 [-ToRecipients <IMicrosoftGraphRecipient[]>] [-UniqueBodyContent <String>] [-UniqueBodyContentType <String>]
 [-UnsubscribeData <String[]>] [-UnsubscribeEnabled] [-WebLink <String>] [-Confirm] [-WhatIf]
 [<CommonParameters>]
```

## DESCRIPTION
Create new navigation property to messages for users

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

### -Attachments
The fileAttachment and itemAttachment attachments for the message.
To construct, see NOTES section for ATTACHMENTS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphAttachment[]
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BccRecipients
The Bcc: recipients for the message.
To construct, see NOTES section for BCCRECIPIENTS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphRecipient[]
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyContent
The content of the item.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyContentType
bodyType

```yaml
Type: System.String
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
message
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphMessage1
Parameter Sets: Create1, CreateViaIdentity1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -BodyPreview
The first 255 characters of the message body.
It is in text format.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Categories
The categories associated with the item

```yaml
Type: System.String[]
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CcRecipients
The Cc: recipients for the message.
To construct, see NOTES section for CCRECIPIENTS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphRecipient[]
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ChangeKey
Identifies the version of the item.
Every time the item is changed, changeKey changes as well.
This allows Exchange to apply changes to the correct version of the object.
Read-only.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CompletedDateTime
A single point of time in a combined date and time representation ({date}T{time}; for example, 2017-08-29T04:00:00.0000000).

```yaml
Type: System.String
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CompletedDateTimeZone
Represents a time zone, for example, 'Pacific Standard Time'.
See below for more possible values.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ConversationId
The ID of the conversation the email belongs to.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ConversationIndexInputFile
Input File for ConversationIndex (Indicates the position of the message within the conversation.)

```yaml
Type: System.String
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CreatedDateTime
The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'

```yaml
Type: System.DateTime
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DueDateTime
A single point of time in a combined date and time representation ({date}T{time}; for example, 2017-08-29T04:00:00.0000000).

```yaml
Type: System.String
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DueDateTimeZone
Represents a time zone, for example, 'Pacific Standard Time'.
See below for more possible values.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Extensions
The collection of open extensions defined for the message.
Nullable.
To construct, see NOTES section for EXTENSIONS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphExtension[]
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -FlagStatus
followupFlagStatus

```yaml
Type: System.String
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -From
recipient
To construct, see NOTES section for FROM properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphRecipient
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -HasAttachments
Indicates whether the message has attachments.
This property doesn't include inline attachments, so if a message contains only inline attachments, this property is false.
To verify the existence of inline attachments, parse the body property to look for a src attribute, such as \<IMG src='cid:image001.jpg@01D26CD8.6C05F070'\>.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
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
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Importance
importance

```yaml
Type: System.String
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InferenceClassification
inferenceClassificationType

```yaml
Type: System.String
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
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
Type: Microsoft.Graph.PowerShell.Models.IUsersMailIdentity
Parameter Sets: CreateViaIdentity1, CreateViaIdentityExpanded1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -InternetMessageHeaders
A collection of message headers defined by RFC5322.
The set includes message headers indicating the network path taken by a message from the sender to the recipient.
It can also contain custom message headers that hold app data for the message.
Returned only on applying a $select query option.
Read-only.
To construct, see NOTES section for INTERNETMESSAGEHEADERS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphInternetMessageHeader[]
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InternetMessageId
The message ID in the format specified by RFC2822.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsDeliveryReceiptRequested
Indicates whether a read receipt is requested for the message.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsDraft
Indicates whether the message is a draft.
A message is a draft if it hasn't been sent yet.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsRead
Indicates whether the message has been read.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IsReadReceiptRequested
Indicates whether a read receipt is requested for the message.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -LastModifiedDateTime
The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time.
For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'

```yaml
Type: System.DateTime
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MentionPreviewIsMentioned
.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Mentions
.
To construct, see NOTES section for MENTIONS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphMention[]
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -MultiValueExtendedProperties
The collection of multi-value extended properties defined for the message.
Nullable.
To construct, see NOTES section for MULTIVALUEEXTENDEDPROPERTIES properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphMultiValueLegacyExtendedProperty[]
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ParentFolderId
The unique identifier for the message's parent mailFolder.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ReceivedDateTime
The date and time the message was received.

```yaml
Type: System.DateTime
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ReplyTo
The email addresses to use when replying.
To construct, see NOTES section for REPLYTO properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphRecipient[]
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Sender
recipient
To construct, see NOTES section for SENDER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphRecipient
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SentDateTime
The date and time the message was sent.

```yaml
Type: System.DateTime
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SingleValueExtendedProperties
The collection of single-value extended properties defined for the message.
Nullable.
To construct, see NOTES section for SINGLEVALUEEXTENDEDPROPERTIES properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphSingleValueLegacyExtendedProperty[]
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -StartDateTime
A single point of time in a combined date and time representation ({date}T{time}; for example, 2017-08-29T04:00:00.0000000).

```yaml
Type: System.String
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -StartDateTimeZone
Represents a time zone, for example, 'Pacific Standard Time'.
See below for more possible values.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Subject
The subject of the message.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ToRecipients
The To: recipients for the message.
To construct, see NOTES section for TORECIPIENTS properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphRecipient[]
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -UniqueBodyContent
The content of the item.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -UniqueBodyContentType
bodyType

```yaml
Type: System.String
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -UnsubscribeData
.

```yaml
Type: System.String[]
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -UnsubscribeEnabled
.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
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
Parameter Sets: Create1, CreateExpanded1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WebLink
The URL to open the message in Outlook Web App.You can append an ispopout argument to the end of the URL to change how the message is displayed.
If ispopout is not present or if it is set to 1, then the message is shown in a popout window.
If ispopout is set to 0, then the browser will show the message in the Outlook Web App review pane.The message will open in the browser if you are logged in to your mailbox via Outlook Web App.
You will be prompted to login if you are not already logged in with the browser.This URL can be accessed from within an iFrame.

```yaml
Type: System.String
Parameter Sets: CreateExpanded1, CreateViaIdentityExpanded1
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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphMessage1

### Microsoft.Graph.PowerShell.Models.IUsersMailIdentity

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphMessage1

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


ATTACHMENTS <IMicrosoftGraphAttachment[]>: The fileAttachment and itemAttachment attachments for the message.
  - `[Id <String>]`: Read-only.
  - `[ContentType <String>]`: The MIME type.
  - `[IsInline <Boolean?>]`: true if the attachment is an inline attachment; otherwise, false.
  - `[LastModifiedDateTime <DateTime?>]`: The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'
  - `[Name <String>]`: The attachment's file name.
  - `[Size <Int32?>]`: The length of the attachment in bytes.

BCCRECIPIENTS <IMicrosoftGraphRecipient[]>: The Bcc: recipients for the message.
  - `[EmailAddress <IMicrosoftGraphEmailAddress>]`: emailAddress
    - `[Address <String>]`: The email address of the person or entity.
    - `[Name <String>]`: The display name of the person or entity.

BODYPARAMETER <IMicrosoftGraphMessage1>: message
  - `[Categories <String[]>]`: The categories associated with the item
  - `[ChangeKey <String>]`: Identifies the version of the item. Every time the item is changed, changeKey changes as well. This allows Exchange to apply changes to the correct version of the object. Read-only.
  - `[CreatedDateTime <DateTime?>]`: The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'
  - `[LastModifiedDateTime <DateTime?>]`: The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'
  - `[Id <String>]`: Read-only.
  - `[Attachments <IMicrosoftGraphAttachment[]>]`: The fileAttachment and itemAttachment attachments for the message.
    - `[Id <String>]`: Read-only.
    - `[ContentType <String>]`: The MIME type.
    - `[IsInline <Boolean?>]`: true if the attachment is an inline attachment; otherwise, false.
    - `[LastModifiedDateTime <DateTime?>]`: The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 would look like this: '2014-01-01T00:00:00Z'
    - `[Name <String>]`: The attachment's file name.
    - `[Size <Int32?>]`: The length of the attachment in bytes.
  - `[BccRecipients <IMicrosoftGraphRecipient[]>]`: The Bcc: recipients for the message.
    - `[EmailAddress <IMicrosoftGraphEmailAddress>]`: emailAddress
      - `[Address <String>]`: The email address of the person or entity.
      - `[Name <String>]`: The display name of the person or entity.
  - `[BodyContent <String>]`: The content of the item.
  - `[BodyContentType <String>]`: bodyType
  - `[BodyPreview <String>]`: The first 255 characters of the message body. It is in text format.
  - `[CcRecipients <IMicrosoftGraphRecipient[]>]`: The Cc: recipients for the message.
  - `[CompletedDateTime <String>]`: A single point of time in a combined date and time representation ({date}T{time}; for example, 2017-08-29T04:00:00.0000000).
  - `[CompletedDateTimeZone <String>]`: Represents a time zone, for example, 'Pacific Standard Time'. See below for more possible values.
  - `[ConversationId <String>]`: The ID of the conversation the email belongs to.
  - `[ConversationIndex <Byte[]>]`: Indicates the position of the message within the conversation.
  - `[DueDateTime <String>]`: A single point of time in a combined date and time representation ({date}T{time}; for example, 2017-08-29T04:00:00.0000000).
  - `[DueDateTimeZone <String>]`: Represents a time zone, for example, 'Pacific Standard Time'. See below for more possible values.
  - `[Extensions <IMicrosoftGraphExtension[]>]`: The collection of open extensions defined for the message. Nullable.
    - `[Id <String>]`: Read-only.
  - `[FlagStatus <String>]`: followupFlagStatus
  - `[From <IMicrosoftGraphRecipient>]`: recipient
  - `[HasAttachments <Boolean?>]`: Indicates whether the message has attachments. This property doesn't include inline attachments, so if a message contains only inline attachments, this property is false. To verify the existence of inline attachments, parse the body property to look for a src attribute, such as <IMG src='cid:image001.jpg@01D26CD8.6C05F070'>.
  - `[Importance <String>]`: importance
  - `[InferenceClassification <String>]`: inferenceClassificationType
  - `[InternetMessageHeaders <IMicrosoftGraphInternetMessageHeader[]>]`: A collection of message headers defined by RFC5322. The set includes message headers indicating the network path taken by a message from the sender to the recipient. It can also contain custom message headers that hold app data for the message.  Returned only on applying a $select query option. Read-only.
    - `[Name <String>]`: Represents the key in a key-value pair.
    - `[Value <String>]`: The value in a key-value pair.
  - `[InternetMessageId <String>]`: The message ID in the format specified by RFC2822.
  - `[IsDeliveryReceiptRequested <Boolean?>]`: Indicates whether a read receipt is requested for the message.
  - `[IsDraft <Boolean?>]`: Indicates whether the message is a draft. A message is a draft if it hasn't been sent yet.
  - `[IsRead <Boolean?>]`: Indicates whether the message has been read.
  - `[IsReadReceiptRequested <Boolean?>]`: Indicates whether a read receipt is requested for the message.
  - `[MentionPreviewIsMentioned <Boolean?>]`: 
  - `[Mentions <IMicrosoftGraphMention[]>]`: 
    - `[Id <String>]`: Read-only.
    - `[Application <String>]`: 
    - `[ClientReference <String>]`: 
    - `[CreatedByAddress <String>]`: The email address of the person or entity.
    - `[CreatedByName <String>]`: The display name of the person or entity.
    - `[CreatedDateTime <DateTime?>]`: 
    - `[DeepLink <String>]`: 
    - `[MentionText <String>]`: 
    - `[MentionedAddress <String>]`: The email address of the person or entity.
    - `[MentionedName <String>]`: The display name of the person or entity.
    - `[ServerCreatedDateTime <DateTime?>]`: 
  - `[MultiValueExtendedProperties <IMicrosoftGraphMultiValueLegacyExtendedProperty[]>]`: The collection of multi-value extended properties defined for the message. Nullable.
    - `[Id <String>]`: Read-only.
    - `[Value <String[]>]`: A collection of property values.
  - `[ParentFolderId <String>]`: The unique identifier for the message's parent mailFolder.
  - `[ReceivedDateTime <DateTime?>]`: The date and time the message was received.
  - `[ReplyTo <IMicrosoftGraphRecipient[]>]`: The email addresses to use when replying.
  - `[Sender <IMicrosoftGraphRecipient>]`: recipient
  - `[SentDateTime <DateTime?>]`: The date and time the message was sent.
  - `[SingleValueExtendedProperties <IMicrosoftGraphSingleValueLegacyExtendedProperty[]>]`: The collection of single-value extended properties defined for the message. Nullable.
    - `[Id <String>]`: Read-only.
    - `[Value <String>]`: A property value.
  - `[StartDateTime <String>]`: A single point of time in a combined date and time representation ({date}T{time}; for example, 2017-08-29T04:00:00.0000000).
  - `[StartDateTimeZone <String>]`: Represents a time zone, for example, 'Pacific Standard Time'. See below for more possible values.
  - `[Subject <String>]`: The subject of the message.
  - `[ToRecipients <IMicrosoftGraphRecipient[]>]`: The To: recipients for the message.
  - `[UniqueBodyContent <String>]`: The content of the item.
  - `[UniqueBodyContentType <String>]`: bodyType
  - `[UnsubscribeData <String[]>]`: 
  - `[UnsubscribeEnabled <Boolean?>]`: 
  - `[WebLink <String>]`: The URL to open the message in Outlook Web App.You can append an ispopout argument to the end of the URL to change how the message is displayed. If ispopout is not present or if it is set to 1, then the message is shown in a popout window. If ispopout is set to 0, then the browser will show the message in the Outlook Web App review pane.The message will open in the browser if you are logged in to your mailbox via Outlook Web App. You will be prompted to login if you are not already logged in with the browser.This URL can be accessed from within an iFrame.

CCRECIPIENTS <IMicrosoftGraphRecipient[]>: The Cc: recipients for the message.
  - `[EmailAddress <IMicrosoftGraphEmailAddress>]`: emailAddress
    - `[Address <String>]`: The email address of the person or entity.
    - `[Name <String>]`: The display name of the person or entity.

EXTENSIONS <IMicrosoftGraphExtension[]>: The collection of open extensions defined for the message. Nullable.
  - `[Id <String>]`: Read-only.

FROM <IMicrosoftGraphRecipient>: recipient
  - `[EmailAddress <IMicrosoftGraphEmailAddress>]`: emailAddress
    - `[Address <String>]`: The email address of the person or entity.
    - `[Name <String>]`: The display name of the person or entity.

INPUTOBJECT <IUsersMailIdentity>: Identity Parameter
  - `[AttachmentId <String>]`: key: attachment-id of attachment
  - `[ExtensionId <String>]`: key: extension-id of extension
  - `[InferenceClassificationOverrideId <String>]`: key: inferenceClassificationOverride-id of inferenceClassificationOverride
  - `[MailFolderId <String>]`: key: mailFolder-id of mailFolder
  - `[MailFolderId1 <String>]`: key: mailFolder-id of mailFolder
  - `[MentionId <String>]`: key: mention-id of mention
  - `[MessageId <String>]`: key: message-id of message
  - `[MessageRuleId <String>]`: key: messageRule-id of messageRule
  - `[MultiValueLegacyExtendedPropertyId <String>]`: key: multiValueLegacyExtendedProperty-id of multiValueLegacyExtendedProperty
  - `[SingleValueLegacyExtendedPropertyId <String>]`: key: singleValueLegacyExtendedProperty-id of singleValueLegacyExtendedProperty
  - `[UserConfigurationId <String>]`: key: userConfiguration-id of userConfiguration
  - `[UserId <String>]`: key: user-id of user

INTERNETMESSAGEHEADERS <IMicrosoftGraphInternetMessageHeader[]>: A collection of message headers defined by RFC5322. The set includes message headers indicating the network path taken by a message from the sender to the recipient. It can also contain custom message headers that hold app data for the message. Returned only on applying a $select query option. Read-only.
  - `[Name <String>]`: Represents the key in a key-value pair.
  - `[Value <String>]`: The value in a key-value pair.

MENTIONS <IMicrosoftGraphMention[]>: .
  - `[Id <String>]`: Read-only.
  - `[Application <String>]`: 
  - `[ClientReference <String>]`: 
  - `[CreatedByAddress <String>]`: The email address of the person or entity.
  - `[CreatedByName <String>]`: The display name of the person or entity.
  - `[CreatedDateTime <DateTime?>]`: 
  - `[DeepLink <String>]`: 
  - `[MentionText <String>]`: 
  - `[MentionedAddress <String>]`: The email address of the person or entity.
  - `[MentionedName <String>]`: The display name of the person or entity.
  - `[ServerCreatedDateTime <DateTime?>]`: 

MULTIVALUEEXTENDEDPROPERTIES <IMicrosoftGraphMultiValueLegacyExtendedProperty[]>: The collection of multi-value extended properties defined for the message. Nullable.
  - `[Id <String>]`: Read-only.
  - `[Value <String[]>]`: A collection of property values.

REPLYTO <IMicrosoftGraphRecipient[]>: The email addresses to use when replying.
  - `[EmailAddress <IMicrosoftGraphEmailAddress>]`: emailAddress
    - `[Address <String>]`: The email address of the person or entity.
    - `[Name <String>]`: The display name of the person or entity.

SENDER <IMicrosoftGraphRecipient>: recipient
  - `[EmailAddress <IMicrosoftGraphEmailAddress>]`: emailAddress
    - `[Address <String>]`: The email address of the person or entity.
    - `[Name <String>]`: The display name of the person or entity.

SINGLEVALUEEXTENDEDPROPERTIES <IMicrosoftGraphSingleValueLegacyExtendedProperty[]>: The collection of single-value extended properties defined for the message. Nullable.
  - `[Id <String>]`: Read-only.
  - `[Value <String>]`: A property value.

TORECIPIENTS <IMicrosoftGraphRecipient[]>: The To: recipients for the message.
  - `[EmailAddress <IMicrosoftGraphEmailAddress>]`: emailAddress
    - `[Address <String>]`: The email address of the person or entity.
    - `[Name <String>]`: The display name of the person or entity.

## RELATED LINKS

