# OAuth
OAuth search

## Authors:
Raghad Al-quraan
Bushra Bilal
Israa Othman 
Fatema Owedah


## Yahoo OAuth
- Yahoo OAuth is an open standard for authorization that Yahoo uses to grant access to user data
- The current version of Yahoo OAuth is Yahoo OAuth 2.0, which provide the following features and benefits:
  - SSL for secure communication
  - No need for signatures
  - Support for a variety of grant types and flows (currently Authorization Code Grant is supported)
## Supported Client Profiles By Yahoo OAuth
- **Server-side Application**
- **Client-side Application**
## Authorization Code Flow for Server-side Apps
![Auth code flow for server-side apps](https://s.yimg.com/oo/cms/products/oauth2/flows_authcode/images/yahoo_auth_flow_04974dd18.png)


## Setup 
  - `.env` requirment 
  - PORT=3000
  - CLIENT_ID=dj0yJmk9QnZ0Y3JQaHdOQnlzJmQ9WVdrOWJVUTJSVlpqTkdVbWNHbzlNQS0tJnM9Y29uc3VtZXJzZWNyZXQmc3Y9MCZ4PTc5
  - CLIENT_SECRET=334866d738e3dd0535fd137c66fd6c7b168121ed
  - SECRET='mysecret'
  - TOKEN_SERVER='https://api.login.yahoo.com/oauth2/request_auth'
  - REMOTE_API='https://api.login.yahoo.com/oauth2/get_token'
  - API_SERVER='http://localhost:3000/oauth'


#### How to initialize/run your application  
  using postman or swagger  
-  signup using yahoo : GET -  http://localhost:3000/oauth/
    + return token 

   

