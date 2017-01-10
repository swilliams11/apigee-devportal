# apigee-devportal
This repository contains links to resources and my notes on about the Apigee DevPortal.


### API Open API Specification
Design API specs here and import them into the DevPortal.
http://apistudio.io/

### Role Based Access Control to API products
A good link to read is
https://community.apigee.com/questions/5321/how-do-you-show-hide-api-products-on-the-app-regis.html

### DevPortal SSO with Okta
This repository is a sample implementation for the OAuth password grant with Okta.
https://github.com/swilliams11/apigee-oauth-password-grant

This article describes how to setup Okta.  The article below describes how to setup DevPortal.
https://community.apigee.com/articles/30051/sso-integration-with-developer-portal-and-okta.html

### DevPortal SSO
A good article to read to enable SSO on the DevPortal is
https://community.apigee.com/articles/29201/sso-integration-via-saml-with-developer-portal.html

Dev Portal commands to set the variable name for

terminus --site=jll-nonprod drush vset simplesamlphp_auth_fname firstName
terminus --site=jll-nonprod drush vset simplesamlphp_auth_lname lastName

Use these commands when you install https://www.drupal.org/project/simplesamlphp_auth and you use the 7.x-3.x-dev version

### API Console To Go
Docs to create an API console for your Dev Portal.
http://docs.apigee.com/developer-services/content/whats-api-console


### API
Generate the Open API spec from the API with our tool.
https://community.apigee.com/articles/15397/api2swagger-open-api-swagger-20-spec-generator-fro.html

This is the most recent version.
https://www.npmjs.com/package/apigee2openapi

Github repository
https://github.com/anil614sagar/apigee2openapi


#### API Studio Spec Generator
http://specgen.apistudio.io/

https://community.apigee.com/articles/25770/openapi-spec-swagger-spec-generator-a-tool-to-gene.html

### weatherapi
The `weatherapi/openapi` folder has two Open API specifications that can be imported into the Dev Portal. Working on adding more resources to this specification.
