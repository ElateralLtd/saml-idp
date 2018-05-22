# How to run against qa-auto-01.elateral-dev.io
* npm install
* node app.js --aud "https://api-dev.elateral-dev.io/authentication/sso/saml2/acs?aid=qa-auto-01&spid=saml-idp" --acs "https://api-dev.elateral-dev.io/authentication/sso/saml2/acs?aid=qa-auto-01&spid=saml-idp"
* in browser navigate to http://localhost:7000/
* Change the user details as required
* Login! 