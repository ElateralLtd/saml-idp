# How to run against qa-auto-01.elateral-dev.io
* npm install

node app.js --aud "https://api-dev01.elateral-dev.io/authentication/sso/saml2/acs?aid=qa-auto-dev01&spid=saml-idp" --acs "https://api-dev01.elateral-dev.io/authentication/sso/saml2/acs?aid=qa-auto-dev01&spid=saml-idp" --httpsPrivateKey "tls.key" --httpsCert "tls.crt" --https true --host lhost.elateral-dev.io

* in browser navigate to https://lhost.elateral-dev.io:7000/
* Change the user details as required
* Login!