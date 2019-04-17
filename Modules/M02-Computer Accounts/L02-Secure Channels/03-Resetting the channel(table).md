<p>﻿## Resetting the channel</p>
<table>
<tbody>
<tr>
<td width="312" valign="top"><img src="/static/3.2.3.png"alt="Screenshot of the Reset Account menu selection obtained by right-clicking on a domain computer, LON-CL1."/></td>
<td width="312" valign="top">
<p>When the secure channel fails, you must reset the computer account. To do this you can use the **Active Directory Users and Computers **snap-in.</p>
<p>When you reset an account the computer's SID remains the same, and the computer maintains its group memberships.</p>
<p>If you prefer to use PowerShell the command is <strong>Test-ComputerSecureChannel -Repair.</strong></p>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td width="78" valign="top"><img src="/static/0.1.7.png"/>
</td>
<td width="552" valign="top">
<p>You can reset a computer account by disjoining the computer from the domain (putting it in a workgroup), and then rejoining the domain. <strong>This is not a good practice</strong> because it has the potential to delete the computer account, which loses the computer’s SID, and its group memberships. When you rejoin the computer to the domain, even when the computer has the same name, the account has a new SID, and all the group memberships of the previous computer object must be recreated.</p>
</td>
</tr>
</tbody>
</table>
