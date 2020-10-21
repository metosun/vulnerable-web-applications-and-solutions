<b>Vulnerability:</b> Stored XSS

<b>Payload:</b> ```<script>alert(1)</script>  and  <script>alert(2)</script>```

<b> Explanation: </b> In the application's "Help" page, user can write to a blog. There is a stored XSS vulnerability. User can write malicious javascript code as input and make it run.

<b>Screenshots:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications-and-solutions/blob/main/Bitcoin%20Website/images/storedxss1.png?raw=true)
![Alt text](https://github.com/metosun/vulnerable-web-applications-and-solutions/blob/main/Bitcoin%20Website/images/storedxss2.png?raw=true)
![Alt text](https://github.com/metosun/vulnerable-web-applications-and-solutions/blob/main/Bitcoin%20Website/images/storedxss3.png?raw=true)

<br><br>

<b>Vulnerability:</b> Local File Inclusion(LFI)

<b>Payload:</b> ```../../../Windows/win.ini```

<b> Explanation: </b> In the application's "Help" page, user can change the parameter in the URL. By changing the parameter, user can some files in the server.

<b>Screenshots:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications-and-solutions/blob/main/Bitcoin%20Website/images/lfi.png?raw=true)

<br><br>

<b>Vulnerability:</b> Cross Site Request Forgery (CSRF)

<b>Payload:</b> Example malicious code can be seen in the screenshot above.<br>

![Alt text](https://github.com/metosun/vulnerable-web-applications-and-solutions/blob/main/Bitcoin%20Website/images/csrf1.png?raw=true)

<b> Explanation: </b> In the application's "Login" functionality, there is CSRF vulnerability. Attacker can make user to do some actions. In the first screenshot above, when a user who is not logged in runs the malicious code, application returns 302 code. It means that attack is not successful. In the second screenshot, when logged in user runs the malicious code, application returns 200 code. It means that attack is successful. 

<b>Screenshots:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications-and-solutions/blob/main/Bitcoin%20Website/images/csrf2.png?raw=true)
![Alt text](https://github.com/metosun/vulnerable-web-applications-and-solutions/blob/main/Bitcoin%20Website/images/csrf3.png?raw=true)

<br><br>

<b>Vulnerability:</b> Reflected XSS

<b>Payload:</b> ```<script>alert(1)</script>```

<b> Explanation: </b> In the application's "About" page, there is a parameter which is vulnerable to reflected XSS. When user inputs the malicious code, the script will be executed. Related screenshot is above.

<b>Screenshots:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications-and-solutions/blob/main/Bitcoin%20Website/images/reflectedxss.png?raw=true)

<br><br>

<b>Vulnerability:</b> SQL Injection

<b>Payload:</b> ```convert(int,(select @@version))  and @@version```

<b> Explanation: </b> There are two SQL Injection vulnerabilities in the application. And both vulnerabilities are Error Based SQL Injections. First vulnerability is shown in first screenshot. When user trying to see products, by changing the parameter in the URL, user can inject into SQL statement. Second vulnerability is shown in second screenshot. In the "About" page, when user clicks to see team members, a request is sent to server. By changing this request's SoapRequest parameter, user can inject into SQL statement.

<b>Screenshots:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications-and-solutions/blob/main/Bitcoin%20Website/images/sqlinjection1.png?raw=true)
![Alt text](https://github.com/metosun/vulnerable-web-applications-and-solutions/blob/main/Bitcoin%20Website/images/sqlinjection2.png?raw=true)

<br><br>
