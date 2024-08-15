<h1>Splunk Investigation 1</h1>

<h2>Description</h2>
I investigated a malicious actor brute-forcing accounts on our organization's website. Using a Splunk search query (sourcetype="stream:http", uri="/xxx/xxx/index.php", http_method=POST), I identified a foreign IP (src_ip) performing 412 HTTP POST requests to our web server (dest_ip). I also discovered the username and password combinations (form_data) used in the attack. Adding '|table timestamp,form_data |sort timestamp asc' to my query improved visualization
<br />

<h2>Lab Certification:</h2>

<p align="center">
<br/>
<img src="https://i.imgur.com/CSbrtgM.png" height="80%" width="80%" alt="portfolio"/>
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
