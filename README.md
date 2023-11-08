1. Go to https://partner.getuhoo.com/login
   ![login](https://github.com/IBehave3/RegisterUhooHome/blob/main/1-login.png)
3. Login with username and password
4. Once logged in go to https://partner.getuhoo.com/customers
5. Click on the customer who has devices registered which you want to connect to API
6. For each device click on their name
7. Copy the Mac Adress from each device
8. To get client_id go here https://partner.getuhoo.com/myaccount
9. Once you have the client_id and the mac addresses go to Postman
10. Go to login-user and fill in username and password to get an access token
11. Click on the AcpResearch project and then Authorization
12. Paste the Access token received into the Bearer token type
13. Go to the uhoo-home-user endpoint
14. Fill in the appropriate values in this form
```
{
    "clientSecret": "",
    "deviceIds": ["", "", ...]
}
```
