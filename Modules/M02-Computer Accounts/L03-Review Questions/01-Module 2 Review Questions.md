<h2>Multiple Choice</h2>
<p>&lt;&lt;display_name:Question 1; max_attempts:3; showanswer:never; weight:1.0&gt;&gt;</p>
<p>You have created OUs for the computers in your organization. Now you would like to automatically redirect all new computers into a NewComputers OU so the IT department will know when new computers have been installed. Which tool should you use?<br />
( ) Active Directory Sites and Domains	
( ) Active Directory Users and Computers	
( ) ADSIEdit	
( ) dsmod	
(x) redircmp</p>
<p>[explanation]	
<b>redircmp</b>. You can use redircmp to redirect all new computers to the NewComputers OU. For example, if the OU is in the Adatum.com domain: Redircmp “OU=NewComputers,DC=Adatum,DC=com”	
[explanation]</p>
<hr />
<h2>Multiple Choice</h2>
<p>&lt;&lt;max_attempts:null;&gt;&gt;</p>
<p>Which PowerShell command can be used to create a new computer account?	
( ) Add-ADComputer	
( ) Enable-ADComputer	
(x) New-ADComputer	
( ) New-ADObject	
( ) Set-ADComputer</p>
<p>[explanation]	
<b>New-ADComputer</b>. The New-ADComputer command can be used to create a new group.	
[explanation]</p>
<hr />
<h2>Multiple Choice</h2>
<p>Aziz has reported he is unable to sign in to the domain. The error message is, “The trust relationship between this workstation and the primary domain failed.” What is likely the problem?		
( ) Bad network connection<br />
(x) Broken secure channel<br />
( ) Computer does not have required security updates<br />
( ) Password policy violations</p>
<p>[explanation]<br />
<b>Broken secure channel</b>. This error message indicates the computer cannot establish a secure channel with a domain controller.<br />
[explanation]</p>
<hr />
<h2>Checkboxes</h2>
<p>Which of the following three things can cause a broken secure channel?<br />
[x] The computer cannot authenticate because the password is out of sync<br />
[x] The computer has been inactive for an extended period<br />
[ ] There is a DNS resolution problem<br />
[ ] There is a network connection problem<br />
[x] The operating system was reinstalled</p>
<p>[explanation]<br />
The operating system was reinstalled, The computer has not been active for an extended period of time, The computer cannot authenticate because the password is out of sync.  Computer accounts and the secure relationships between computers and their domain are robust. Nevertheless, these scenarios can cause a broken channel.<br />
[explanation]</p>
<hr />
<h2>Multiple Choice</h2>
<p>To fix a broken secure channel what should you do?<br />
( ) Disable the computer account and rejoin the computer to the domain.<br />
( ) Delete the existing computer account and create a new computer account.<br />
( ) Disjoin the computer account and rejoin the computer to the domain.<br />
(x) Reset the computer account and rejoin the computer to the domain.</p>
<p>[explanation]<br />
<b>Reset the computer account</b>. When the secure channel fails, you should reset the computer account. By default, the netdom reset and Test-ComputerSecureChannel solutions will try to reset the password at the computer and domain level. If successful, a reboot is not required. If not, a reboot is required.<br />
[explanation]</p>
<hr />
<h2>Multiple Choice</h2>
<p>You are on the domain controller and creating a file for offline domain join. You are using the djoin.exe command. Which parameter will create the computer account in AD DS?<br />
( ) /localos<br />
(x) /provision<br />
( ) /requestodj<br />
( ) /windowspath</p>
<p>[explanation]<br />
<b>provision</b>. The provision parameter will create and configure the computer account for the computer that will be joining the domain.<br />
[explanation]</p>
<hr />
<h2>Multiple Choice</h2>
<p>You have identified a problem with a broken channel on LON-CL1. Your first step on the Domain Controller is to right-click LON-CL1 and<br />
( ) delete the account<br />
( ) disable the account<br />
( ) disjoin the account<br />
(x) reset the account</p>
<p>[explanation]<br />
<b>Reset the account</b>. When the secure channel fails, you must reset the computer account.<br />
[explanation]</p>
<hr />
<h2>Multiple Choice</h2>
<p>Which of the following is not a benefit of pre-staging a computer account?<br />
( ) Enforces delegated control<br />
( ) Enforces the group policy settings<br />
( ) Enforces the OU structure<br />
(x) Ensures there is not a broken channel</p>
<p>[explanation]<br />
<b> Ensures there is not a broken channel </b>. Pre-staging a computer account will not prevent a broken channel.<br />
[explanation]</p>
<hr />
<h2>Multiple Choice</h2>
<p>A computer changes its password approximately every<br />
( ) other day<br />
(x) every 30 days<br />
( ) every 45 days<br />
( ) every 60 days</p>
<p>[explanation]<br />
<b> every 30 days </b>. A computer changes its password in the domain approximately every 30 days.<br />
[explanation]</p>
