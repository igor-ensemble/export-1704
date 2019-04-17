<h2>Multiple Choice</h2>
<p>The following histogram shows the results of a survey about people’s preferred coffee temperature.<br />
<img src="/static/0.1.7.png" alt="" />
Which statement about the data is true ?  (<strong>Choose one</strong>)</p>
<p>( ) More people prefer their coffee between 153 and 160.3 degrees than between 167.6 and 174.9 degrees.<br />
( ) Most people prefer their coffee above 189.5 degrees.<br />
( ) 5 people prefer their coffee between 204.1 and 211.4 degrees.<br />
(x) Nobody prefers their coffee at 200 degrees.</p>
<hr />
<h2>Multiple Choice</h2>
<p>&lt;&lt;display_name:Question 1; max_attempts:2; showanswer:never; weight:1.0&gt;&gt;
Which PowerShell command can be used to create a new user?
( ) Enable-ADAccount<br />
( ) New-ADAccount<br />
(x) New-ADUser<br />
( ) Set-ADUser<br />
or New-ADAccount</p>
<p>[explanation]<br />
<b>New-ADUser</b>. The New-ADUser command can be used to create a new user. For example, New-ADUser -Name &quot;Ed Meadows&quot;.<br />
[explanation]</p>
<hr />
<h2>Multiple Choice</h2>
<p>Which setting ensures users do not reuse the same password too often?<br />
( ) Complexity requirements<br />
(x) Enforce password history<br />
( ) Maximum password age<br />
( ) Minimum password age</p>
<p>[explanation]<br />
<b>Enforce password history</b>. The Enforce password history setting determines the number of unique, new passwords that must be associated with a user account before an old password can be reused.<br />
[explanation]</p>
<hr />
<h2>Multiple Choice</h2>
<p>Which setting can be used to set the number of failed logon tries that are allowed before a user account is locked out?<br />
( ) Account lockout duration<br />
(x) Account lockout threshold<br />
( ) Complexity requirements<br />
( ) Reset account lockout counter</p>
<p>[explanation]<br />
<b>Account lockout threshold</b>. The Account lockout threshold setting determines the number of failed logon tries that are allowed before a user account is locked out. Set this value high enough to allow for mistyped passwords, but low enough to minimize the chances of a successful brute force attack on a password.<br />
[explanation]</p>
<hr />
<h2>Multiple Choice</h2>
<p>Your organization’s administrators need to use more stringent passwords. Which of the following should you implement?<br />
( ) Complexity requirements<br />
(x) Fine-grained password policies<br />
( ) Password permissions<br />
( ) User profile redirection</p>
<p>[explanation]<br />
<b>Fine-grained password policies</b>. You can use fine-grained password policies to specify multiple password policies, and to apply different password restrictions and account lockout policies to different sets of users in a single domain. For example, administrators may have different password requirements that are stricter than the policies for a user.<br />
[explanation]</p>
<hr />
<h2>Multiple Choice</h2>
<p>What of the following AD DS attributes represents a user’s logon name?<br />
( ) cn<br />
( ) DisplayName<br />
( ) Name<br />
(x) sAMAccountName</p>
<p>[explanation]<br />
<b>sAMAccountName</b>. When users sign in, they use their sAMAccountName. In some cases, the value of sAMAccountName can match the value of other attributes.<br />
[explanation]</p>
<hr />
<h2>Multiple Choice</h2>
<p>Your company has experienced several accounts being locked out. You suspect that a denial of service (DoS) attack is responsible.  Which of the following settings should you use to temporarily halt the attack?<br />
( ) Set the account lockout duration to 0.<br />
(x) Set the account lockout threshold to 0.<br />
( ) Set the account lockout duration to 999.<br />
( ) Set the account lockout threshold to 999.</p>
<p>[explanation]<br />
<b>Set the account lockout threshold to 0</b>. Setting the account lockout threshold to 0 will prevent accounts from being locked out which temporarily halts the attack.<br />
[explanation]</p>
<hr />
<h2>Multiple Choice</h2>
<p>You are setting up a new branch office with 25 user accounts. Much of the user account information is the same, so you have created a user template. When you run the New-ADUser command which parameter should you use to pass the template?<br />
(x) -Instance<br />
(  ) -Template<br />
(  ) -Path<br />
(  ) -Settings</p>
<p>[explanation]<br />
<b>-Instance</b>. The Instance parameter can be used to create a new user from a template.<br />
[explanation]</p>
<hr />
<h2>Multiple Choice</h2>
<p>Brad is a member of several groups. Which of following can be used to view his overall password permissions?<br />
(  ) Additive group permissions<br />
(  ) Administrator account permissions<br />
(  ) Fine-grained password settings<br />
(x) Resultant password permissions</p>
<p>[explanation]<br />
<b>Resultant password permissions</b>. You can use the ADAC to view a user’s resultant password permissions and ensure they have the correct permissions.<br />
[explanation]</p>
<hr />
<h2>Multiple Choice</h2>
<p>You are creating a new user using Windows PowerShell. You have used New-ADUser and Set-ADAccountPassword. Which command should you use next?<br />
(x) Enable-ADAccount<br />
( ) Enable-ADObject<br />
( ) Set-ADAccount<br />
( ) Set-ADUser</p>
<p>[explanation]<br />
<b>Enable-ADAccount</b>. Without this command the user account will be disabled.<br />
[explanation]</p>
<hr />
<h2>Multiple Choice</h2>
<p>You are creating a new user but the password (Password) keeps throwing an error. What is likely the problem?<br />
( ) You have to create the user before assigning the password.<br />
(x) The password does not meet complexity requirements.<br />
( ) You do not have permission to create a user.<br />
( ) The user already has a password.</p>
<p>[explanation]<br />
<b>The password does not meet complexity requirements</b>. Even when you are creating a new user where the password will be changed, the password must meet complexity requirements.<br />
[explanation]</p>
