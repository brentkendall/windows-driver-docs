---
title: WIA\_IPS\_PRINTER\_ENDORSER\_GRAPHICS
description: The WIA\_IPS\_PRINTER\_ENDORSER\_GRAPHICS property is used to report whether the Imprinter/Endorser item supports graphics and image data along with text.
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
ms.assetid: F2550D8F-DF66-4184-909B-F0CCB68AD7C6
keywords: ["WIA_IPS_PRINTER_ENDORSER_GRAPHICS Imaging Devices"]
topic_type:
- apiref
api_name:
- WIA_IPS_PRINTER_ENDORSER_GRAPHICS
api_location:
- Wiadef.h
api_type:
- HeaderDef
---

# WIA\_IPS\_PRINTER\_ENDORSER\_GRAPHICS


The **WIA\_IPS\_PRINTER\_ENDORSER\_GRAPHICS** property is used to report whether the Imprinter/Endorser item supports graphics and image data along with text. Graphics are typically used by the device to print/endorse near the text, or as a background image. The WIA minidriver creates and maintains this property.

## <span id="ddk_wia_ipa_depth_si"></span><span id="DDK_WIA_IPA_DEPTH_SI"></span>


Property Type: VT\_I4 (Boolean)

Valid Values: WIA\_PROP\_NONE

Access Rights: Read-only

Remarks
-------

If **WIA\_IPS\_PRINTER\_ENDORSER\_GRAPHICS** is supported and set to a value of nonzero (True), the Imprinter/Endorser supports graphic data.

This property is required for all Imprinter/Endorser items, but it can be implemented to always report a value of 0 (False).

Requirements
------------

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Header</p></td>
<td>Wiadef.h (include Wiadef.h)</td>
</tr>
</tbody>
</table>

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bimage\image%5D:%20WIA_IPS_PRINTER_ENDORSER_GRAPHICS%20%20RELEASE:%20%2811/13/2017%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")



