<b>Vulnerability:</b> Cross Site Scripting - Reflected (GET)

<b>Payload:</b> ```<script>alert('xss');</script>```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications-and-solutions/blob/main/bwapp/images/xss-reflected(get).png?raw=true)

<b>Reason:</b> As you can see in the screenshot above, there is no input validation for data coming via get request.
![Alt text](https://github.com/metosun/vulnerable-web-applications-and-solutions/blob/main/bwapp/images/xss-reflected(get)-reason.png?raw=true)

<br><br>

<b>Vulnerability:</b> Cross Site Scripting - Reflected (POST)

<b>Payload:</b> ```<script>alert('xss');</script>```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications-and-solutions/blob/main/bwapp/images/xss-reflected(post).png?raw=true)

<b>Reason:</b> As you can see in the screenshot above, there is no input validation for data coming via post request.
![Alt text](https://github.com/metosun/vulnerable-web-applications-and-solutions/blob/main/bwapp/images/xss-reflected(post)-reason.png?raw=true)

<br><br>

<b>Vulnerability:</b> Cross Site Scripting - Reflected (JSON)

<b>Payload:</b> ```"}]}';alert('xss');</script>```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications-and-solutions/blob/main/bwapp/images/xss-reflected(json).png?raw=true)

<b>Reason:</b> As you can see in the screenshot above, there is no input validation for data coming via json request. So, application directly injects the json value into script.
![Alt text](https://github.com/metosun/vulnerable-web-applications-and-solutions/blob/main/bwapp/images/xss-reflected(json)-reason.png?raw=true)

<br><br>

<b>Vulnerability:</b> Cross Site Scripting - Reflected (AJAX/JSON)

<b>Payload:</b> ```<img src=x onerror=javascript:alert('xss')>```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications-and-solutions/blob/main/bwapp/images/xss-reflected(ajax-json).png?raw=true)

<b>Reason:</b> As you can see in the screenshot above, there is no input validation for data coming via ajax request. So, application directly injects the json value into html.
![Alt text](https://github.com/metosun/vulnerable-web-applications-and-solutions/blob/main/bwapp/images/xss-reflected(ajax-json)-reason.png?raw=true)

<br><br>

<b>Vulnerability:</b> Cross Site Scripting - Reflected (AJAX/XML)

<b>Payload:</b> ```&lt;img src=&apos;#&apos; onerror=&apos;alert(1)&apos;&gt;```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications-and-solutions/blob/main/bwapp/images/xss-reflected(ajax-xml).png?raw=true)

<b>Reason:</b> As you can see in the screenshot above, there is no input validation for data coming via ajax request. So, application directly injects the xml data into html.
![Alt text](https://github.com/metosun/vulnerable-web-applications-and-solutions/blob/main/bwapp/images/xss-reflected(ajax-xml)-reason.png?raw=true)

<br><br>


