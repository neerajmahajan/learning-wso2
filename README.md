# learning-wso2

* https://docs.wso2.com/display/ESB490/Sending+a+Simple+Message+Through+the+ESB

###### API Manager

* Security
* Rate limit
* Monitoring


* API Publisher through developer portal
* API Store


##### OAAuth 2.0

###### Authentication types

* Simple login
   * User enter username and password.
   * backend service validate user and send a cookie in user browser to maintain a session.
* Single sign on across sites (SAML)
* Mobile app login
* Delegated authorization (OATH)


##### OAuth 2.0 terminology

* Resource owner (me, I)
* Client (main site which  which want to access your data eg yelp want to access your google contacts)
* Authorization server (google)
* Resource server (eg google contact api)
* Authorization grant (A thing that proves person has click yes)
* Redirect URI (where the authorization redirect back)
* Access token (Token given by authorization server to access data defined by Authorization grant)

####### OAuth Flow

* Authorization code (front + back)
* Implicit (front channel only)
* Resource owner password credentials (back channel only)
* Client credentials 



