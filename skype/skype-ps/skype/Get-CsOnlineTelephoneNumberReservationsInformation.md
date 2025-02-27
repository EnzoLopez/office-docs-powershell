---
external help file: Microsoft.Rtc.Management.Hosted.dll-help.xml 
online version: https://docs.microsoft.com/powershell/module/skype/get-csonlinetelephonenumberreservationsinformation
applicable: Skype for Business Online
title: Get-CsOnlineTelephoneNumberReservationsInformation
schema: 2.0.0
manager: bulenteg
author: tomkau
ms.author: tomkau
ms.reviewer:
---

# Get-CsOnlineTelephoneNumberReservationsInformation

## SYNOPSIS
Use the Get-CsOnlineTelephoneNumberReservationsInformation to retrieve information about the total number of telephone numbers which can reserved per session, and the maximum active reservations per session.

**Note**:

As of April 30, 2022, the existing Skype for Business PowerShell cmdlets for telephone number search and related activities will be deprecated and will no longer be available for use. The new Teams PowerShell cmdlets for telephone number search and related activities are already available. For more details, see [New-CsOnlineTelephoneNumberOrder](https://docs.microsoft.com/powershell/module/teams/new-csonlinetelephonenumberorder?view=teams-ps).

## SYNTAX

```
Get-CsOnlineTelephoneNumberReservationsInformation [-Tenant <Guid>] [-DomainController <Fqdn>] [-Force]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
This cmdlet is used to see the number of active reservations, reserved telephone numbers, maximum reservations supported per session, and maximum telephone numbers that can be reserved per session.

The console output of this cmdlet will be in the following form:

Get-CsOnlineTelephoneNumberReservationsInformation

RunspaceId : 37c11bb0-3064-4e36-a0af-05efe9ee2bd3

ActiveReservationsCount : 0

ActiveReservedNumbersCount : 0

MaximumActiveReservationsCount : 10

MaximumActiveReservedNumbersCount : 200

## EXAMPLES

### -------------------------- Example 1 --------------------------
```
Get-CsOnlineTelephoneNumberReservationsInformation
```

This example returns the number of active reservations, reserved telephone numbers, maximum reservations supported per session, and maximum telephone numbers that can be reserved per session.


## PARAMETERS

### -Confirm
The Confirm switch causes the command to pause processing, and requires confirmation to proceed.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf
Applicable: Skype for Business Online

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DomainController
This parameter is reserved for internal Microsoft use.

```yaml
Type: Fqdn
Parameter Sets: (All)
Aliases: DC
Applicable: Skype for Business Online

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Force
The Force switch specifies whether to suppress warning and confirmation messages.
It can be useful in scripting to suppress interactive prompts.
If the Force switch isn't provided in the command, you're prompted for administrative input if required.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 
Applicable: Skype for Business Online

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Tenant
This parameter is reserved for internal Microsoft use.

```yaml
Type: Guid
Parameter Sets: (All)
Aliases: 
Applicable: Skype for Business Online

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
The WhatIf switch causes the command to simulate its results.
By using this switch, you can view what changes would occur without having to commit those changes.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi
Applicable: Skype for Business Online

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (https://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### None


## OUTPUTS

### LacReservationInformation object

## NOTES

## RELATED LINKS

