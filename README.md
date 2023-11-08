1. Go to https://partner.getuhoo.com/login
2. Login with username and password
   ![login](https://github.com/IBehave3/RegisterUhooHome/blob/main/1-login.png)
3. Once logged in go to https://partner.getuhoo.com/customers
   ![customers](https://github.com/IBehave3/RegisterUhooHome/blob/main/2-customers.png)
4. Click on the customer who has devices registered which you want to connect to API
   ![customer-name](https://github.com/IBehave3/RegisterUhooHome/blob/main/3-customer-name.png)
5. For each device click on their name
    ![device-name](https://github.com/IBehave3/RegisterUhooHome/blob/main/4-device-name.png)
6. Copy the Mac Adress from each device
   ![copy-mac-address](https://github.com/IBehave3/RegisterUhooHome/blob/main/5-copy-mac-address.png)
7. To get client_id go here https://partner.getuhoo.com/myaccount
   ![my-account](https://github.com/IBehave3/RegisterUhooHome/blob/main/6-my-account.png)
   ![developer](https://github.com/IBehave3/RegisterUhooHome/blob/main/7-developer.png)
   ![copy-client-id](https://github.com/IBehave3/RegisterUhooHome/blob/main/8-copy-client-id.png)
8. Once you have the client_id and the mac addresses go to Postman
10. Go to login-user and fill in username and password to get an access token
   ![postman-login](https://github.com/IBehave3/RegisterUhooHome/blob/main/9-postman-login.png)
   ![access-token](https://github.com/IBehave3/RegisterUhooHome/blob/main/10-access-token.png)
12. Click on the AcpResearch project and then Authorization
13. Paste the Access token received into the Bearer token type
   ![set-token](https://github.com/IBehave3/RegisterUhooHome/blob/main/12-set-token.png)
14. Go to the uhoo-home-user endpoint
15. Fill in the appropriate values in this form
    ![update-api](https://github.com/IBehave3/RegisterUhooHome/blob/main/13-update-api.png)

