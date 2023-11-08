1. Go to https://partner.getuhoo.com/login
2. Login with username and password
3. Once logged in go to https://partner.getuhoo.com/customers
4. Click on the customer who has devices registered which you want to connect to API
5. For each device click on their name
6. Copy the Mac Adress from each device
7. To get client_id go here https://partner.getuhoo.com/myaccount
8. Once you have the client_id and the mac addresses go to Postman
9. Go to login-user and fill in username and password to get an access token
10. Click on the AcpResearch project and then Authorization
11. Paste the Access token received into the Bearer token type
12. Go to the uhoo-home-user endpoint
13. Fill in the appropriate values in this form
```
{
    "clientSecret": "",
    "deviceIds": ["", "", ...]
}
```
