<b>Vulnerability:</b> HTML Injection - Reflected(GET) 

<b>Payload:</b> ```<h1><b>injection</b></h1>```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/HTML-injection-reflected(get).png?raw=true)

<b>Reason:</b> As you can see in the screenshot above, there is no input validation for data coming via get request.
![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/html-injection-reflected(get)-reason.png?raw=true)

<br><br>

<b>Vulnerability:</b> HTML Injection - Reflected(POST) 

<b>Payload:</b> ```<h1><b>injection</b></h1>```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/HTML-injection-reflected(post).png?raw=true)

<b>Reason:</b> As you can see in the screenshot above, there is no input validation for data coming via post request.
![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/html-injection-reflected(get)-reason.png?raw=true)


<br><br>

<b>Vulnerability:</b> HTML Injection - Reflected(URL) 

<b>Payload:</b> ```<h1><b>injection</b></h1>```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/HTML-injection-reflected(url).png?raw=true)

![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/HTML-injection-reflected(url)2.png?raw=true)

<b>Reason:</b> As you can see in the screenshot above, there is no input validation for data coming from URL.
![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/HTML-injection-reflected(url)-reason.png?raw=true)

<br><br>

<b>Vulnerability:</b> HTML Injection - Stored(Blog) 

<b>Payload:</b> ```<h1><b>injection</b></h1>```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/HTML%20injection-stored(blog).png?raw=true)


<b>Reason:</b> As you can see in the screenshot above, input validation is only for SQLInjection. There is no input validation for HTML tag escaping etc.
![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/HTML%20injection-stored(blog)-reason.png?raw=true)

<br><br>

<b>Vulnerability:</b> IFrame Injection 

<b>Payload:</b> https://google.com

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/iframeinjection.png?raw=true)


<b>Reason:</b> As you can see in the screenshot above, there is no input validation for data coming from URL. We can not see the page for google because of Google's policy. However, we can understand that we can inject malicious site into the iframe.
![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/iframeinjection-reason.png?raw=true)

<br><br>

<b>Vulnerability:</b> OS Command Injection

<b>Payload:</b> ```www.nsa.gov;whoami;id```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/os-command-injection.png?raw=true)


<b>Reason:</b> As you can see in the screenshot above, there is no input validation for search parameter.
![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/os-command-injection-reason.png?raw=true)


<br><br>

<b>Vulnerability:</b> OS Command Injection- Blind

<b>Payload:</b> ```$(sleep 5;echo 8.8.8.8)```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/os-command-injection-blind.png?raw=true)


<b>Reason:</b> As you can see in the screenshot above, there is no input validation for search parameter.
![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/os-command-injection-reason.png?raw=true)



<br><br>

<b>Vulnerability:</b> PHP Code Injection

<b>Payload:</b> ```phpinfo()```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/php-injection.png?raw=true)


<b>Reason:</b> As you can see in the screenshot above, there is no input validation for search parameter. So, server runs the php code directly.<br>
![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/php-injection-reason.png?raw=true)


<br><br>

<b>Vulnerability:</b> Server Side Includes(SSI) Injection

<b>Payload:</b> ```<!--#exec cmd="id"-->```<br>```<!--#exec cmd="whoami"-->```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/ssi-injection1.png?raw=true)
![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/ssi-injection2.png?raw=true)


<b>Reason:</b> As you can see in the screenshot above, there is no input validation.<br>
![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/html-injection-reflected(get)-reason.png?raw=true)



<br><br>

<b>Vulnerability:</b> Server Side Includes(SSI) Injection

<b>Payload:</b> ```<!--#exec cmd="id"-->```<br>```<!--#exec cmd="whoami"-->```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/sqlinjection(get-search).png?raw=true)


<b>Reason:</b> As you can see in the screenshot above, there is no input validation. So, the input used in SQL statement.<br>
![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/sqlinjection(get-search)reason.png?raw=true)
