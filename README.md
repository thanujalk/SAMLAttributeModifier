# SAML Attribute Modifier
---
This component allows to modify attributes in the SAML authentication response.

## Building From Source

Clone this repository first (`https://github.com/thanujalk/SAMLAttributeModifier.git`) and use Maven install to build
`mvn clean install`.

## Deploying to IS 5.2.0

* Copy SAMLAttributeModifier-1.0.0.jar file to wso2is-5.2.0/repository/components/dropins folder
* Update /home/thanuja/products/is/wso2is-5.2.0/repository/conf/identity/identity.xml as follows,
````xml
<SAMLSSOAssertionBuilder>org.wso2.custom.saml.SAMLAttributeModifier</SAMLSSOAssertionBuilder>
````
