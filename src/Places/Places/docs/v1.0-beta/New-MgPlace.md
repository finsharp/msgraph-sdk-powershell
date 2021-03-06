---
external help file:
Module Name: Microsoft.Graph.Places
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.places/new-mgplace
schema: 2.0.0
---

# New-MgPlace

## SYNOPSIS
Add new entity to places

## SYNTAX

### CreateExpanded (Default)
```
New-MgPlace [-AddressCity <String>] [-AddressCountryOrRegion <String>] [-AddressPostalCode <String>]
 [-AddressPostOfficeBox <String>] [-AddressState <String>] [-AddressStreet <String>] [-AddressType <String>]
 [-DisplayName <String>] [-GeoCoordinateAccuracy <Double>] [-GeoCoordinateAltitude <Double>]
 [-GeoCoordinateAltitudeAccuracy <Double>] [-GeoCoordinateLatitude <Double>]
 [-GeoCoordinateLongitude <Double>] [-Id <String>] [-Phone <String>] [-Confirm] [-WhatIf] [<CommonParameters>]
```

### Create
```
New-MgPlace -BodyParameter <IMicrosoftGraphPlace1> [-Confirm] [-WhatIf] [<CommonParameters>]
```

## DESCRIPTION
Add new entity to places

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

### -AddressCity
The city.

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

### -AddressCountryOrRegion
The country or region.
It's a free-format string value, for example, 'United States'.

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

### -AddressPostalCode
The postal code.

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

### -AddressPostOfficeBox
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

### -AddressState
The state.

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

### -AddressStreet
The street.

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

### -AddressType
physicalAddressType

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
place
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IMicrosoftGraphPlace1
Parameter Sets: Create
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -DisplayName
The name associated with the place.

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

### -GeoCoordinateAccuracy
The accuracy of the latitude and longitude.
As an example, the accuracy can be measured in meters, such as the latitude and longitude are accurate to within 50 meters.

```yaml
Type: System.Double
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -GeoCoordinateAltitude
The altitude of the location.

```yaml
Type: System.Double
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -GeoCoordinateAltitudeAccuracy
The accuracy of the altitude.

```yaml
Type: System.Double
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -GeoCoordinateLatitude
The latitude of the location.

```yaml
Type: System.Double
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -GeoCoordinateLongitude
The longitude of the location.

```yaml
Type: System.Double
Parameter Sets: CreateExpanded
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
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Phone
The phone number of the place.

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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphPlace1

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphPlace1

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER <IMicrosoftGraphPlace1>: place
  - `[Id <String>]`: Read-only.
  - `[AddressCity <String>]`: The city.
  - `[AddressCountryOrRegion <String>]`: The country or region. It's a free-format string value, for example, 'United States'.
  - `[AddressPostOfficeBox <String>]`: 
  - `[AddressPostalCode <String>]`: The postal code.
  - `[AddressState <String>]`: The state.
  - `[AddressStreet <String>]`: The street.
  - `[AddressType <String>]`: physicalAddressType
  - `[DisplayName <String>]`: The name associated with the place.
  - `[GeoCoordinateAccuracy <Double?>]`: The accuracy of the latitude and longitude. As an example, the accuracy can be measured in meters, such as the latitude and longitude are accurate to within 50 meters.
  - `[GeoCoordinateAltitude <Double?>]`: The altitude of the location.
  - `[GeoCoordinateAltitudeAccuracy <Double?>]`: The accuracy of the altitude.
  - `[GeoCoordinateLatitude <Double?>]`: The latitude of the location.
  - `[GeoCoordinateLongitude <Double?>]`: The longitude of the location.
  - `[Phone <String>]`: The phone number of the place.

## RELATED LINKS

