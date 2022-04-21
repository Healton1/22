

Click the button below to deploy to Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## 0. Attention

Deployment requires registration of a heroku account, a email is required when registering a heroku account (otherwise the verification code cannot be brushed out). 

An email address that can receive verification codes normally (@qq.com, @163.com are not acceptable):
- gmail (Best) 
- Outlook <https://login.live.com/> here.

## 1. Verification

After the server is deployed, open app to display the webpage normally. After the address is filled with the path (for example: <https://test.herokuapp.com/static>), the 403 page is displayed, which means the deployment is successful.

## 2. Client Configuration



**or**



(Change test to your own app name)

Copy the details after opening and import it to the client.

**or**

Manual configuration:

```sh
Server: test.herokuapp.com (change test to your app name)
Port: 443
Password: The password filled in during deployment

Hostname: Same as Server
```

Those without a client can also download from here (Android):
