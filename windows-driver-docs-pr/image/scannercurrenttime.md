---
title: ScannerCurrentTime element
description: The required ScannerCurrentTime element indicates the current date and time according to the scanner's internal clock.
MS-HAID:
- 'wsdss\_status\_fb6cab49-ca64-48f5-8822-b8a4ab2c94ee.xml'
- 'image.scannercurrenttime'
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
ms.assetid: 7103fdb4-dfa4-40b0-b20e-022e2a42bf5c
keywords: ["ScannerCurrentTime element Imaging Devices"]
topic_type:
- apiref
api_name:
- wscn ScannerCurrentTime
api_type:
- Schema
---

# ScannerCurrentTime element


The required **ScannerCurrentTime** element indicates the current date and time according to the scanner's internal clock.

Usage
-----

``` syntax
<wscn:ScannerCurrentTime>
  text
</wscn:ScannerCurrentTime>
```

Attributes
----------

There are no attributes.

Text value
----------

Required. Any valid value for the dateTime type. For more information about dateTime, see XML Schema Part 2: Datatypes Second Edition.**dateTimedateTime**

## Child elements


There are no child elements.

## Parent elements


<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th>Element</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>[<strong>ScannerStatus</strong>](scannerstatus.md)</p></td>
</tr>
</tbody>
</table>

Remarks
-------

The scanner's internal clock does not have to be a real-time clock. The clock can start at zero (0001-01-01T00:00:00Z) and start counting up when the device is turned on.

All times are based on the time at startup, so the client can calculate duration and relative time by reading the **ScannerCurrentTime** element and comparing it to the previous time value.

## <span id="see_also"></span>See also


[**ScannerStatus**](scannerstatus.md)

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bimage\image%5D:%20ScannerCurrentTime%20element%20%20RELEASE:%20%2811/8/2017%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")




