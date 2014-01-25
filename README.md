OAuth 2.0 (RFC 6749)  Apigee Proxies 
==============================

Apigee Proxy to help understand and try out [OAuth 2.0 RFC 6749](http://tools.ietf.org/html/rfc6749). 

I created these proxies in the process of understanding OAuth 2.0. The RFC 6749 provides infromation about various endpoints involved; expected request and responses for each of the API calls. It is good to try out these API to get good hold on the whole OAuth 2.0 Protocol. 

Apigee Edge provides a very easy way to experience OAuth 2.0 - hence this proxy!

## Usage Guidelines

### Apigee Environment Setup

* Get a free [Apigee Edge Account ](https://enterprise.apigee.com/)
* Create an new API Proxy using the bundle file _oauth20_proxy.zip_. 
* Create an Product, Developer, Developer App in Apigee. Sample JSON defintions of these are provided in the _org_data_ directory
* Add the proxy to the product created in previous step.
* Now all the server side setup is done!
 
### Chrome Postman Setup

* _oauth20_rfc_postman.json_ is a [postman](http://www.getpostman.com) collection JSON that can imported into postman.
*  Collection contains the APIs described in the OAuth 2.0 RFC.
*  Customize the values in it and try out the APIs.

### More Info
* Apigee OAuth 2.0 Support - [Authorize requests using OAuth 2.0](http://apigee.com/docs/api-services/content/authorize-requests-using-oauth-20)
* Good Explanation Of OAuth 2.0 By Aaron - [OAuth 2 Simplified](http://aaronparecki.com/articles/2012/07/29/1/oauth2-simplified) 
* If you wondered (like me) why Authorization Code is required in OAuth 2.0 - [Stack Overflow Question](http://stackoverflow.com/questions/13387698/why-is-there-an-authorization-code-flow-in-oauth2-when-implicit-flow-works-s)

-----

And i wrote this using [LightPaper](http://clockworkengine.com/lightpaper-mac/) - love this markdown editor!