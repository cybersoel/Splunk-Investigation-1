<h1>Splunk Investigation 1</h1>

<h2>Description</h2>
I was assigned to investigate a potential security breach involving a malicious actor attempting to brute force user accounts on our organization's website.
To begin the investigation, I leveraged Splunk's powerful search capabilities. I crafted a precise search query using the following parameters:
sourcetype="stream:http" uri="/xxx/xxx/index.php" http_method=POST
This query allowed me to focus on HTTP traffic specifically targeting the administrator login page of our website. By analyzing the results, I uncovered a suspicious pattern of activity originating from a single foreign IP address (src_ip).
<br />

<h2>Lab Certification:</h2>

<p align="center">
<br/>
<img src="" height="80%" width="80%" alt="portfolio"/>
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
