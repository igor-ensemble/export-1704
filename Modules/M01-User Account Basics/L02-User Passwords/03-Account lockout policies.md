<p>﻿## Account lockout policies
 
<img src="....\Linked_Image_Files\1.2.3.png" alt="Screenshot of the GPMC showing the Account lockout policies node. The GPOs discussed in the text are shown. " /><br />
<a href="https://technet.microsoft.com/en-us/library/cc757692(v=ws.10).aspx#w2k3tr_sepol_accou_set_tdtx">Account lockout policies</a> enable you to define whether accounts should be locked if there are too many logon tries with invalid passwords. Most organizations implement account lockout policies to prevent attackers from using password-guessing techniques to gain access to a network. Using this approach provides a level of security. However, it also exposes your organization to a denial of service attack because an attacker can run scripts to guess user passwords and lock out user accounts. If you decide not to implement account lockout policies, it's important that you monitor failed account logon tries in real time to prevent an attacker from taking advantage of this configuration. There are three corresponding Group Policy settings.</p>
<table>
<tbody>
<tr>
<td width="152" valign="top">
<p><strong>Setting</strong></p>
</td>
<td width="179" valign="top">
<p><strong>Description</strong></p>
</td>
<td width="179" valign="top">
<p><strong>Values</strong></p>
</td>
</tr>
<tr>
<td width="152" valign="top">
<p><strong>Account lockout duration</strong></p>
</td>
<td width="179" valign="top">
<p>Defines the number of minutes that a locked account remains locked. After the specified number of minutes, the account automatically unlocks.</p>
</td>
<td width="179" valign="top">
<p>Normal setting:  30 minutes</p>
<p>Administrator must unlock the account: 0 minutes </p>
</td>
</tr>
<tr>
<td width="152" valign="top">
<p><strong>Account lockout threshold</strong></p>
</td>
<td width="179" valign="top">
<p>Determines the number of failed logon tries that are allowed before a user account is locked out. Set this value high enough to allow for mistyped passwords, but low enough to make sure the failure of brute force attempts to guess a password.</p>
</td>
<td width="179" valign="top">
<p>Account is never locked out: 0 attempts</p>
<p>Typical: 3 – 5 attempts</p>
</td>
</tr>
<tr>
<td width="152" valign="top">
<p><strong>Reset account lockout counter after</strong></p>
</td>
<td width="179" valign="top">
<p>How many minutes must elapse after a failed logon attempt before the bad logon counter is reset to zero. This setting applies when a user has typed in a password incorrectly, but the user has not exceeded the account lockout threshold.</p>
</td>
<td width="179" valign="top">
<p>Recommended value: 30 minutes</p>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td width="78"><img src="/static/0.1.5.png">
</td>
<td width="534">
<p>There is a practical exercise on <strong>Group Policy Password Settings</strong>.</p>
</td>
</tr>
</tbody>
</table>
