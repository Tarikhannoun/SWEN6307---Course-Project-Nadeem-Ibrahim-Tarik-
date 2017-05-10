Please find the attached, our deliverable for the first Milestone (Service interface implementation: interface + data), include the following:

1- "Read Me" doc. to clarify the exists web server and web services(business use, relation between them "composition", Input/Output)

2- JBoss Server - DMZ Middleware 1 (Code, WSDL, sampile data) 

3- Apache Server  - LAN Middleware 2 (Code, WSDL, sampile data) 

Notes:

1- Web server1 (simulate Public DMZ) (Middleware1): built on JBoss, use SOAP technology and return XML format


2- Web server2 (simulate Local LAN) (Middleware2): built on Apache, use SOAP technology and return JSON format 
3- We tasted all web services that built on apache and jboss by using SOAP UI vesion 5.3.0
4- we implemented Apache web services on public server (www.optimal.ps), any one can use them:
http://www.optimal.ps/SWEN6307/getCustomerInfo.php?wsdl
http://www.optimal.ps/SWEN6307/getCustomerBills.php?wsdl
http://www.optimal.ps/SWEN6307/getCustomerServices.php?wsdl
http://www.optimal.ps/SWEN6307/login.php?wsdl
http://www.optimal.ps/SWEN6307/bankAuthntectionPayment.php?wsdl
http://www.optimal.ps/SWEN6307/updatePayment.php?wsdl
