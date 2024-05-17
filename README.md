<img src="./src/assets/images/logo/logo256.png" height="128" align="left" valign="top"
  alt="windows command to regEdit capsLock" />
<br>
<b>regEdit caps-lock key into a control key</b><br>
<sup><sub>
Deep in the chaotic regime, slight changes in structure almost always cause vast changes in behavior.
</sub></sup>
<br><br><br><br>

<table>
<tr><td>
<pre>
regedit HKEY_LOCAL_MACHINE/System/CurrentControlSet/Control/keyboard layout
click on it and add a new binary key named Scancode Map
Set the key to: 00 00 00 00 | 00 00 00 00 | 02 00 00 00 | 1D 00 3A 00 | 00 00 00 00
</pre>
</td></tr>
</table>
