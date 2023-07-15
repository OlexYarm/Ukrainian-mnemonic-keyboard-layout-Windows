README.txt

A Ukrainian mnemonic/phonetic keyboard layout for Windows 10 and Windows 11.

The Ukrainian mnemonic/phonetic keyboard layout was developed with Microsoft Keyboard Layout Creator (MSKLC) Version 1.4.
Initial version of the layout "ukr-mne" was tested on Windows 10 and worked as expected.
Testing on Windows 11 showed problem with accessing several letters assigned with Ctrl key. Somehow Windows 11 blocked that keys.
So, another version of layout "ukr-m01" was developed with use of AltGr key.
The MSKLC help says: "The Alt key on the right side of the keyboard (to the right of the space bar). The term "AltGr" comes from "Alt Graphic". The behavior of the AltGr key is always identical to pressing the Control + Alt key simultaneously."
Unfortunately the MSKLC does not have functionality to configure use of Alt key in keyboard layout, the AltGr was only alternative possibility to Ctrl.

The Microsoft Keyboard Layout Creator (MSKLC) Version 1.4 could be downloaded from Microsoft web site https://www.microsoft.com/en-us/download/details.aspx?id=102134 and installed on Windows 10/11.

Installation Windows 10

There are two options:
1) Download installation package located if folder "ukr-mne" and run installed "setup.exe".
The installation package was built with MSKLC.

2) Download source file "Ukr-Mnemonic.klc" with keyboard layout definition, build installation package with MSKLC and install keyboard layout as with option #1.
This option required installation of MSKLC to build installation package for keyboard layout, but it guarantee that installation package does not contains any malware.
Also, it allows to modify layout as desired.

Notes

1) Majority of Ukrainian letters are accessible without Control or Alt keys (please see screenshots "MSKLC Ukr normal.png" and "MSKLC Ukr shift.png").
Exception are four letters ї Ї ґ Ґ (please see screenshots "MSKLC Ukr ctrl.png" and "MSKLC Ukr ctrl shift.png"):
ї - accessible with Ctrl i
Ї - accessible with Ctrl Shift i
ґ - accessible with Ctrl ' (apostrophe)
Ґ - accessible with Ctrl Shift ' (apostrophe)

VK_I
i U+0456
Shift I U+0406
Ctrl ї U+0457
Shift+Ctrl Ї U+0407

VK_OEM_7
'
Shift "
Ctrl ґ U+0491
Shift+Ctrl Ґ U+0490

2) Majority of non-alphanumeric keys are accessible without Control or Alt keys (please see screenshots "MSKLC Ukr normal.png" and "MSKLC Ukr shift.png").
Exception nine six keys ` ~ [ ] { } \ | / (please see screenshots "MSKLC Ukr ctrl.png" and "MSKLC Ukr ctrl shift.png"):

`
~
[ - accessible with Ctrl [
] - accessible with Ctrl ]
{ - accessible with Ctrl Shift [
} - accessible with Ctrl Shift ]
\ - accessible with Ctrl \
| - accessible with Ctrl Shift \
/ - accessible with Ctrl /

VK_OEM_3
ю U+044e
Shift Ю U+042e
Ctrl ` U+0060
Shift+Ctrl ~ U+007e

VK_OEM_4
ш U+0448
Shift Ш U+0428
Ctrl [ U+005b
Shift+Ctrl { U+007b

VK_OEM_6
щ U+0449
Shift Щ U+0429
Ctrl ] U+005d
Shift+Ctrl } U+007d

VK_OEM_5
є U+0454
Shift U+0404
Ctrl \ U+005c
Shift+Ctrl | U+007c

VK_OEM_2
ь U+044c
Ctrl / U+002f

Installation Windows 11

There are two options:
1) Download installation package located if folder "ukr-m01" and run installed "setup.exe".
The installation package was built with MSKLC.

2) Download source file "Ukr-Mnemonic-V0.1.klc" with keyboard layout definition, build installation package with MSKLC and install keyboard layout as with option #1.
This option required installation of MSKLC to build installation package for keyboard layout, but it guarantee that installation package does not contains any malware.
Also, it allows to modify layout as desired.

Notes

1) All notes above for Windows 10 are valid for Windows 11 with exception that AltGr key should be used instead of Ctlr key.
My experience showed that this is not very convenient, I'll try to find better solution.

2) Layout screenshots for Windows 11 are files Ukr-M01.jpg, Ukr-M01AltGr.jpg, Ukr-M01Ctrl.jpg, Ukr-M01Shft.jpg, Ukr-M01ShftAltGr.jpg, Ukr-M01ShftCtrl.jpg.

3) Windows 11 should be restarted after every installation/deinstallation of keyboard layout.
After several installation/deinstallation while testing layout on Windows 11 I had to manually clean Windows Registry.

4) I did not find a way to configure use of Alt key while creating layout with MSKLC.

5) I did not figure out how to change language description at the end of *.klc file with MSKLC.
I created new version of keyboard layout based on initial version, changed layout name and description, but language description at the end of *.klc file was inherited from initial version.
I had to change manually that with binary editor.
