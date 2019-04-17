<h2>Lab: Directory Services</h2>
<p>These are the tasks in your graded lab. Be sure you can complete the tasks in the time allotted and that you ready to be tested. The tasks will be repeated in the testing environment.</p>
<p><strong>TASK 1</strong>: Create a new top level Organization Unit (OU) named Merger in the <g>ADATUM</g> domain. In the Merger OU, create a security group with a Global scope named Auditors.</p>
<p><strong>TASK 2</strong>: Create a new user account for Jim Healy with the following properties.</p>
<ul>
<li>User logon name: <strong><g>jimh</g></strong></li>
<li>Password: <strong>Pa55w.rd</strong></li>
<li>Job Title: <strong>Auditor</strong></li>
<li>Group: <strong>Auditors</strong></li>
</ul>
<p><strong>TASK 3</strong>: Create a fine-grained password policy and apply it to the Auditors group.</p>
<ul>
<li>Name: <strong>Auditors</strong></li>
<li>Precedence: <strong>10</strong></li>
<li>Minimum password length: <strong>10</strong></li>
<li><strong>Enforce lockout policy with 10 failed logon attempts allowed</strong></li>
</ul>
<p><strong>TASK 4</strong>: Add a DHCP reservation to the London Office DHCP scope for LON-CL1.</p>
<ul>
<li>Name: <strong>LON-CL1</strong></li>
<li>IP Address: <strong>172.16.0.201</strong></li>
<li>MAC Address: <strong>00-15-5D-A3-97-61</strong></li>
<li>Support Types: <strong>DHCP</strong></li>
</ul>
<p><strong>TASK 5</strong>: Create a new organizational unit named MyComputers in the root of the <g>ADATUM</g> domain so that computer accounts are by default created in the MyComputers OU when computers are joined to the domain.</p>
<p><strong>TASK 6</strong>: Edit the <g>these User Configuration</g> Personalization settings.</p>
<ul>
<li>Enable Screen Saver Timeout to 600 seconds.</li>
<li>Password protect the screen saver.</li>
</ul>
<hr />
<h2>LTI component</h2>
<h3>lti_consumer:</h3>
<h6>Enter the LTI ID for the external LTI provider. This value must be the same LTI ID that you entered in the LTI Passports setting on the Advanced Settings page.</h6>
<pre><code>LTI ID:xtreme
</code></pre>
<h6>Enter the URL of the external tool that this component launches. This setting is only used when Hide External Tool is set to False.</h6>
<pre><code>LTI URL: https://labs.microsoftlabsonline.com/mslconnection/authlti 
</code></pre>
<h6>Add the key/value pair for any custom parameters, such as the page your e-book should open to or the background color for this component.</h6>
<h6>Ex. [&quot;page=1&quot;, &quot;color=white&quot;]</h6>
<pre><code>Custom Parameters:[&quot;content_title=AZURE203x-LaaS&quot;]
</code></pre>
<h6>Enter the text on the button used to launch the third party application.</h6>
<h6>This setting is only used when Hide External Tool is set to False and LTI Launch Target is set to Modal or New Window.</h6>
<pre><code>Button Text:Launch the Graded Lab Environment
</code></pre>
<h6>Enter 'inline' if you want the LTI content to open in an IFrame in the current page.</h6>
<h6>Enter 'modal' if you want the LTI content to open in a modal window in the current page.</h6>
<h6>Enter 'new_window' if you want the LTI content to open in a new browser window. This setting is only used when Hide External Tool is set to False. </h6>
<pre><code>LTI Launch Target:new_window 
</code></pre>
<h6>Enter the name that students see for this component.</h6>
<h6>Analytics reports may also use the display name to identify this component.</h6>
<pre><code>Display Name:Launch Lab 
</code></pre>
<h6>Enter 'true' if this component will receive a numerical score from the external LTI system.</h6>
<pre><code>Scored:true 
</code></pre>
<h6>Enter the number of points possible for this component.</h6>
<h6>The default value is 1.0. This setting is only used when Scored is set to True.</h6>
<pre><code>Weight:1.0 
</code></pre>
<h6>Enter 'true' to request the user's email address, otherwise enter 'false'</h6>
<pre><code>Request user's email:true 
</code></pre>
<h6>Enter 'true' to request the user's username address, otherwise enter 'false'</h6>
<pre><code>Request user's username:true 
</code></pre>
<h6>Enter a description of the third party application.</h6>
<h6>If requesting username and/or email, use this text box to inform users why their username and/or email will be forwarded to a third party application.</h6>
<pre><code>LTI Application Information:
</code></pre>
<h6>Enter the desired pixel height of the iframe which will contain the LTI tool.</h6>
<h6>This setting is only used when Hide External Tool is set to False and LTI Launch Target is set to Inline.</h6>
<pre><code>Inline Height:800
</code></pre>
<h6>Enter the desired viewport percentage height of the modal overlay which will contain the LTI tool.</h6>
<h6>This setting is only used when Hide External Tool is set to False and LTI Launch Target is set to Modal.</h6>
<pre><code>Modal Height:80
</code></pre>
<h6>Enter the desired viewport percentage width of the modal overlay which will contain the LTI tool.</h6>
<h6>This setting is only used when Hide External Tool is set to False and LTI Launch Target is set to Modal.</h6>
<pre><code>Modal Width:80
</code></pre>
<h6>Enter 'true' if you want to use this component as a placeholder for syncing with an external grading system rather than launch an external tool.</h6>
<h6>This setting hides the Launch button and any IFrames for this component.</h6>
<pre><code>Hide External Tool:false
</code></pre>
<h6>Enter 'true' to allow third party systems to post grades past the deadline; otherwise enter 'false'</h6>
<pre><code>Accept grades past deadline:True
</code></pre>
