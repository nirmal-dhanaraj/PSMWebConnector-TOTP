# PSMWebConnector-TOTP
In this post I'm going to explain about the high level steps for devloping/configuring CyberArk Web Based PSM Connector Componant for LastPass Portal.
The Web based Connector will use Time-based one-time password (TOTP) is a computer algorithm that generates a one-time password (OTP) that uses the current time as a source of uniqueness.

# Step1: Create a LastPass account and enable Good MFA
We all know LastPass is a SaaS service and I've creaed a trial account (https://lastpass.com/create-account.php). This is the account I'm going onbaord onbaord into CyberArk and enable trasparant connections to end users and this will also provide options to follow TOTP feature of CyberArk.
Generate a Chrome based web Connector - for similicity I've used CyberArk Plugin Generator utility to create a Web Connector.. So that I'll get all correct field names until I get the MFA page on the LastPass Portal. Note LastPass is a SaaS service and I've creaed a trial account (https://lastpass.com/create-account.php) 
