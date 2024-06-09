## Banking-backend
<br/>

Through this project, I hope to learn all laraval, django, and ASP.NET core.
<br/>

Endpoints: 
--- 
Description: Logs the user in the account.
<br/>
Endpoint: /accounts/login/
<br/>
HTTP Method: POST
<br/>
JWT Authorization: None
<br/>
Input: email, password
<br/>
Output: access_token, refresh_token
<br/>

---
Description: Used to register a new user into the bank.
<br/>
Endpoint: /accounts/register/
<br/>
HTTP Method: POST
<br/>
JWT Authorization: None
<br/>
Input: email, birthday (yyyy-mm-dd), firstname, lastname, password, password2
<br/>
Output: None
<br/>

---
Description: Logs the current user out.
<br/>
Endpoint: /accounts/logout/
<br/>
HTTP Method: POST
<br/>
JWT Authorization: Required
<br/>
Input: None
<br/>
Output: None
<br/>

---
Description: registers a new notification for the given user
<br/>
Endpoint: /notification/
<br/>
HTTP Method: POST
<br/>
JWT Authorization: Required
<br/>
Input: email, text
<br/>
Output: None
<br/>

---
Description: gets all the notifications for the current user
<br/>
Endpoint: /notification/
<br/>
HTTP Method: GET
<br/>
JWT Authorization: Required
<br/>
Input: None
<br/>
Output: Object/QuerySet
<br/>

---
