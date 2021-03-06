---
title: OID_DOT11_WFD_GROUP_START_PARAMETERS
author: windows-driver-content
description: When set, the OID_DOT11_WFD_GROUP_START_PARAMETERS object identifier (OID) provides the startup parameters for a Wi-Fi Direct (WFD) Group Owner (GO).
ms.assetid: E71D6292-2265-4D41-A4E9-430B6AB7B702
ms.author: windowsdriverdev
ms.date: 08/08/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
keywords: 
 -OID_DOT11_WFD_GROUP_START_PARAMETERS Network Drivers Starting with Windows Vista
---

# OID\_DOT11\_WFD\_GROUP\_START\_PARAMETERS


**Important**  The [Native 802.11 Wireless LAN](https://msdn.microsoft.com/library/windows/hardware/ff560690) interface is deprecated in Windows 10 and later. Please use the WLAN Device Driver Interface (WDI) instead. For more information about WDI, see [WLAN Universal Windows driver model](https://msdn.microsoft.com/library/windows/hardware/dn897672).

 

When set, the OID\_DOT11\_WFD\_GROUP\_START\_PARAMETERS object identifier (OID) provides the startup parameters for a Wi-Fi Direct (WFD) Group Owner (GO).

The data type for this OID is the [**DOT11\_WFD\_GROUP\_START\_PARAMETERS**](https://msdn.microsoft.com/library/windows/hardware/hh406659) structure.

This OID is sent to the miniport only when the group is started after a GO negotiation or invitation exchange. The WFD GO port must also support starting the group with appropriate start parameters when this OID is not set.

Requirements
------------

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Version</p></td>
<td><p>Supported starting with Windows 8.</p></td>
</tr>
<tr class="even">
<td><p>Header</p></td>
<td>Windot11.h (include Windot11.h)</td>
</tr>
</tbody>
</table>

## See also


[**DOT11\_WFD\_GROUP\_START\_PARAMETERS**](https://msdn.microsoft.com/library/windows/hardware/hh406659)

 

 




