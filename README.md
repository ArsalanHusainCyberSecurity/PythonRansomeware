<h1>Creating Ransomeware in Pyhton </h1>

<h2>Description</h2>
I have designed a project to demonstrate the intricacies of potentially harmful software development using Python. This is aimed at providing an in-depth understanding of how malicious tools can be crafted. In this project, I've illustrated the steps to create a demonstration ransomware using the cryptography library in Python, specifically Fernet. Additionally, I've curated a controlled environment that showcases a collection of sample Python scripts for educational insight.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Linode</b> 
- <b>Linux</b>
- <b>Python</b>

<h2>Environments Used </h2>

- <b>Ubuntu 22.04LTS</b>

<h2>Program walk-through:</h2>

<p align="center">
First I created my linode machine: <br/>
<img src="https://cdn.discordapp.com/attachments/1139535912439656528/1139535954642735206/image.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Logged into the machine via SSH:  <br/>
<img src="https://cdn.discordapp.com/attachments/1139535912439656528/1139537671388135514/image.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Created some test files for encryption as well as a test directory: <br/>
<img src="https://cdn.discordapp.com/attachments/1139535912439656528/1139538298444976258/image.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Created a script that will discover all files in a directory:  <br/>
<img src="https://cdn.discordapp.com/attachments/1139535912439656528/1139540483283107914/image.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Discovery working as intended:  <br/>
<img src="https://cdn.discordapp.com/attachments/1139535912439656528/1139542008248143902/image.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Added an encryption key to the script:  <br/>
<img src="https://cdn.discordapp.com/attachments/1139535912439656528/1139543161350406305/image.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Test to see if the script works:  <br/>
<img src="https://cdn.discordapp.com/attachments/1139535912439656528/1139543979319373824/image.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Now that we know it works we can actually encrpyt the files:  <br/>
<img src="https://cdn.discordapp.com/attachments/1139535912439656528/1139545516930240522/image.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://cdn.discordapp.com/attachments/1139535912439656528/1139546646548586626/image.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://cdn.discordapp.com/attachments/1139535912439656528/1139546818280165437/image.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Added a decryption key and a threatening message:  <br/>
<img src="https://cdn.discordapp.com/attachments/1139535912439656528/1139549432828940358/image.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The whole process:  <br/>
<img src="https://cdn.discordapp.com/attachments/1139535912439656528/1139549752703324190/image.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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

