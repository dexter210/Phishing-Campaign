<h1>Phishing Campaign</h1>


<h2>Description</h2>
This project involves setting up a simulated phishing campaign using GoPhish to test security awareness among a targeted group of users.
The goal of this project is to evaluate user susceptibility to phishing attacks and improve cybersecurity awareness through controlled simulations.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Gophish</b> 
- <b>Railway</b>

<h2>Environments Used </h2>

- <b>Windows 11</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
1. Setting Up Gophish on Railway

Sign up on Railway using GitHub and authorize the Railway App.

Review and agree to the Terms of Service and Fair Use Policy if prompted.

Deploy the Gophish one-click starter template on Railway.

Configure deployment settings and launch Gophish on the default Railway domain.<br/>
<img src=https://i.imgur.com/yvPL5pK.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
2. Accessing the Gophish Admin Interface

After deployment, find login credentials in the deployment logs.

Access the Gophish admin server using the provided username and password.<br/>
<img src=https://i.imgur.com/imyZ4Ns.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
3. Configuring Campaign Elements

Users & Groups - Define target users who will receive phishing emails.

Phishing Email Templates - Create custom emails, including attachments.

Sending Profiles - Configure SMTP relay details for email delivery.

Landing Pages - Set up fake login pages for credential capture. <br/>
<img src="https://i.imgur.com/l4iMdw0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/yJl0pLe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/EUpffFh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/UAMogAB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />
<br />
4. Launching the Phishing Campaign

Navigate to the Campaigns page in Gophish.

Click "New Campaign" and fill in the required fields.

Use pre-configured templates for emails, landing pages, and sending profiles.

Set the URL for the Gophish listener.

Click "Launch Campaign" to initiate the phishing simulation. You now have a Live campaign! <br/>
<img src="https://i.imgur.com/Egqa9Vz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Need to know : 
When setting up a phishing campaign for ethical hacking, penetration testing, or security awareness training, it’s crucial to configure your Virtual Private Server (VPS) properly to prevent email spoofing. Email spoofing can cause your emails to be flagged as spam or outright blocked. <br/>
<br />

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
