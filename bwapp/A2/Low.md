<b>Vulnerability:</b> Broken Authentication - CAPTCHA Bypassing

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications-and-solutions/blob/main/bwapp/images/captcha-bypassing.png?raw=true)

<b>Explanation: </b> Using Burp, prevent the application to load captcha box. Then enter the credentials and delete captcha_user parameter from the request package. You are logged in. It is because, captcha box php document creates captcha variable. By preventing it to load the page, the variable is not set and not controlled by the application. 

<br><br>

<b>Vulnerability:</b> Broken Authentication - Insecure Login Forms

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications-and-solutions/blob/main/bwapp/images/insecure-login-forms.png?raw=true)

<b>Explanation: </b> As we can see in the screenshot, credentials are located in the html. They are typed with backgroun color. So, we need to highlight them or just look at the html source.
<br><br>

<b>Vulnerability:</b> Broken Authentication - Logout Management

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications-and-solutions/blob/main/bwapp/images/logout-reason.png?raw=true)

<b>Explanation: </b> As we can see in the screenshot, there is no destroying mechanism for session id. So, we can use two tabs and logout from one tab. We can still use our sesion on other tab.

<br><br>


<b>Vulnerability:</b> Broken Authentication - Password Attacks


<b>Explanation: </b> Because there is no preventing mechanism, we can brute force the login form in the application.

<br><br>

<b>Vulnerability:</b> Broken Authentication - Weak Passwords

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications-and-solutions/blob/main/bwapp/images/weak-password-reason.png?raw=true)

<b>Explanation: </b> As we can see in the screenshot, credentials are easy to guess. So, by trying first things came into mind, we can log in to the application.

<br><br>

<b>Vulnerability:</b> Session Management - Administrative Portals

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications-and-solutions/blob/main/bwapp/images/administrative-portal1.png?raw=true)
![Alt text](https://github.com/metosun/vulnerable-web-applications-and-solutions/blob/main/bwapp/images/administrative-portal2.png?raw=true)
![Alt text](https://github.com/metosun/vulnerable-web-applications-and-solutions/blob/main/bwapp/images/administrative-portal-reason.png?raw=true)

<b>Explanation: </b> As we can see in the screenshots, administrative check is done by checking parameter transferred with the URL. By changing the value from 0 to 1, we can have access to administrative portal.

<br><br>


<b>Vulnerability:</b> Session Management - Cookies (HTTPOnly)

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications-and-solutions/blob/main/bwapp/images/cookies(httponly).png?raw=true)

<b>Explanation: </b> Cookies do not have httponly flag. So, as we can see in the screenshot, we can access the cookies from javascript. It is not considered as secure for cookie management.
<br><br>


<b>Vulnerability:</b> Session Management - Cookies (Secure)

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications-and-solutions/blob/main/bwapp/images/cookies(secure).png?raw=true)

<b>Explanation: </b> Cookies do not have secure flag. So, cookies can transferred using insecure protocols(such as HTTP). It is considered as insecure for cookie management.
<br><br>


<b>Vulnerability:</b> Session Management - Session ID in URL

<b>Screenshot:</b>

![Alt text](https://github.com/metosun/vulnerable-web-applications-and-solutions/blob/main/bwapp/images/sesionidinurl.png?raw=true)

<b>Explanation: </b> Session ID is being carried in URL. It is insecure way of handling session ids.

<br><br>

