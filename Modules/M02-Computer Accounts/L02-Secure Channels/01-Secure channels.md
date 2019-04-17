<h2>Secure channels</h2>
<p><strong>A secure channel is used for all computer communications.</strong></p>
<p>The NetLogon service uses the computer credentials to log on to the domain, which establishes the <em>secure channel</em> with a domain controller. This secure channel between a computer and a domain controller is used for all communication with the domain.</p>
<p>If the computer is unable to sign in successfully, the secure channel is not established. The effect is similar to when a user enters the wrong user name or password. In both circumstances, the user is not able to authenticate to the domain.</p>
<p><strong>Know the symptoms of a broken secure channel.</strong></p>
<p>A <em>broken</em> computer account manifests itself with a variety of symptoms, error messages, and event-log entries. The most common signs of computer account problems are <strong>sign-in messages</strong> and <strong>event log messages</strong>.</p>
<p><strong>Sign-in messages</strong></p>
<p><img src="/Modules/Linked_Image_Files/3.2.1.png" alt="Screenshot of a user login error: The trust relationship between this workstation and the primary domain failed. " /></p>
<p>Messages at sign-in indicate that a domain controller cannot be contacted, that the computer account might be missing, that the password on the computer account is incorrect, or that the trust relationship (also called <em>the secure relationship</em>) between the computer and the domain has been lost.</p>
<p><strong>Event log messages</strong></p>
<p><strong><img src="/Modules/Linked_Image_Files/3.2.1-2.png" alt="Screenshot of NetLogon Event ID 5722: The session setup from the computer failed to authenticate. Access denied. " /></strong></p>
<p>Error messages or events in the event log indicate similar problems or suggest that passwords, trusts, secure channels, or relationships with the domain or a domain controller have failed.</p>
