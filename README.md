# Cisco IOS XE Commands Syntax Highlighting

<br />

<img src="assets/cisco-logo.png" alt="Cisco Logo" title="Cisco" width="300" style="display: block;"/>

<br />

> This is an enhanced version of the **User Defined Language (UDL)** made by LuisPisco. His UDL is found [here](https://github.com/notepad-plus-plus/userDefinedLanguages/blob/master/UDLs/Cisco_IOS_byLuisPisco.xml).

After Installing [NotePad++](https://notepad-plus-plus.org/downloads/), place the `Cisco_IOS_XE_byOsamaAbbas.udl.xml` file within the `%AppData%\Notepad++\userDefineLangs` folder, and restart NotePad++.

Files with extensions `.cisco`, `.ios`, `.xe`, `.log`, `.txt`, `.conf`, and `.config` will automagically use this new UDL as their default language when opened with NotePad++. Remove or add any extension when desired.

To change this behavior:

1. Open the `Cisco_IOS_XE_byOsamaAbbas.udl.xml` file.
2. For example, remove `txt` from the `ext` property in `<UserLang>`.

```xml
<UserLang name="Cisco IOS XE" ext="cisco ios xe log conf config" udlVersion="2.0">
```

3. Save the UDL file.
4. Restart NotePad++.

## Preview

![Preview](assets/preview.jpg)
