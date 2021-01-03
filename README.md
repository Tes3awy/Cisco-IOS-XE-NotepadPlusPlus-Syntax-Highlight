# Cisco IOS XR Commands Syntax Highlighting

<br />

<img src="cisco-logo.png" alt="Cisco Logo" title="Cisco" width="300" style="display: block;"/>

<br />

> **This is an enhanced version of the User Defined Language (UDL) made by LuisPisco. His UDL can be found [here](https://github.com/notepad-plus-plus/userDefinedLanguages/blob/master/UDLs/Cisco_IOS_byLuisPisco.xml).**

After Installing [NotePad++](https://notepad-plus-plus.org/downloads/), place the `Cisco_IOS_XR_byOsamaAbbas.udl.xml` file within `%AppData%\Notepad++\userDefineLangs`, and restart NotePad++.

Files with extensions `.cisco`, `.ios`, `.xr`, `.log`, and `.txt` will automatically use this UDL as their default language when opened with NotePad++.

To change this behavior, open `Cisco_IOS_XR_byOsamaAbbas.udl.xml` file, remove `txt` from `ext` property in <UserLang>, save the file, and restart NotePad++.

```xml
<UserLang name="Cisco IOS XR" ext="cisco ios xr log txt" udlVersion="3.0">
```

## Preview

![Preview](preview.jpg)