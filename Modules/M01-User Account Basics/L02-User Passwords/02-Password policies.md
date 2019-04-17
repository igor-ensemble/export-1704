<h2>Password policies</h2>
<p><img src="../..\Linked_Image_Files\1.2.2.png" alt="Screenshot of the GPMC with the Password Policies node highlighted. GPOs discussed in the text (such as Enforce password history) are shown. " /></p>
<p>When www securing your user accounts use the <a href="https://technet.microsoft.com/en-us/library/cc757692(v=ws.10).aspx#w2k3tr_sepol_accou_set_kuwh">Password Policy</a> settings. You should configure the properties of the passwords that users might select. Use these settings to make sure users don’t select simple <g>passwords,</g> or passwords that have been recently used. You can only have one standard password policy in a domain.</p>
<table>
<tbody>
<tr>
<td width="229" valign="top">
<p><strong>Setting</strong></p>
</td>
<td width="271" valign="top">
<p><strong>Description</strong></p>
</td>
<td width="236" valign="top">
<p><strong>Values</strong></p>
</td>
</tr>
<tr>
<td width="229" valign="top">
<p><strong>Enforce password history</strong></p>
</td>
<td width="271" valign="top">
<p>The number of unique, new passwords that must be associated with a user account before an old password can be reused.</p>
</td>
<td width="236" valign="top">
<p>Default setting: 24 passwords</p>
</td>
</tr>
<tr>
<td width="229" valign="top">
<p><strong>Maximum password age</strong></p>
</td>
<td width="271" valign="top">
<p>Number of days that a password can be used before the user must change it.</p>
</td>
<td width="236" valign="top">
<p>Recommended setting: 42 days</p>
</td>
</tr>
<tr>
<td width="229" valign="top">
<p><strong>Minimum password age</strong></p>
</td>
<td width="271" valign="top">
<p>Number of days that a password must be used before the user can change it.</p>
</td>
<td width="236" valign="top">
<p>Default setting: 1 day</p>
</td>
</tr>
<tr>
<td width="229" valign="top">
<p><strong>Minimum password length</strong></p>
</td>
<td width="271" valign="top">
<p>Minimum number of characters that a user’s password must contain.</p>
</td>
<td width="236" valign="top">
<p>Default setting: 7 characters</p>
<p>High security: 15 characters</p>
</td>
</tr>
<tr>
<td width="229" valign="top">
<p><strong>Complexity requirements</strong></p>
</td>
<td width="271" valign="top">
<p>Required password characteristics. Don't disable.</p>
</td>
<td width="236" valign="top">
<p>Does not contain your name or user name. Has at least six characters. Contains characters from different charsets <strong><sup>[1]</sup></strong></p>
</td>
</tr>
</tbody>
</table>
<p><sup>[1]</sup>Contains characters from 3 of these 4 for charsets: Uppercase letters [A–Z]; Lowercase letters [a–z]; Numerals [0–9]; Special, non-alphanumeric characters, such as !@#)(*&amp;^% .</p>
