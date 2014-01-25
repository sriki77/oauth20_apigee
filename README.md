OAuth 2.0 (RFC 6749)  Apigee Proxies 
==============================

Apigee Proxy to help understand and try out [OAuth 2.0 RFC 6749](http://goo.gl/XkoanG). 

I created these proxies in the process of understanding OAuth 2.0. The RFC 6749 provides infromation about various endpoints involved; expected request and responses for each of the API calls. It is good to try out these API to get good hold on the whole OAuth 2.0 Protocol. 

Apigee Edge provides a very easy way to experience OAuth 2.0 - hence this proxy!

## Usage Guidelines

### Apigee Environment Setup

* Get a free [Apigee Edge Account ](http://goo.gl/cCeu2I)
* Create an new API Proxy using the bundle file _oauth20_proxy.zip_. 
* Create an Product, Developer, Developer App in Apigee. Sample JSON defintions of these are provided in the _org_data_ directory
* Add the proxy to the product created in previous step.
* Now all the server side setup is done!
 
### Chrome Postman Setup

* _oauth20_rfc_postman.json_ is a [postman](http://goo.gl/Am8StQ) collection JSON that can imported into postman.
*  Collection contains the APIs described in the OAuth 2.0 RFC.
*  Customize the values in it and try out the APIs.

### More Info
* Apigee OAuth 2.0 Support - [Authorize requests using OAuth 2.0](http://goo.gl/ZHroQt)
* Good Explanation Of OAuth 2.0 By Aaron - [OAuth 2 Simplified](http://goo.gl/uXKWuM) 
* If you wondered (like me) why Authorization Code is required in OAuth 2.0 - [Stack Overflow Question](http://goo.gl/TqHxHZ)

-----

And i wrote this using [LightPaper](http://goo.gl/5It4jg) - love this markdown editor!