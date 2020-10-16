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
