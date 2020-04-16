# WhatsAppIntegrationWithGupShup
Whats app API integration with gupshup

1.	Go to following link and create login
https://www.gupshup.io/whatsappassistant/#/whatsapp-dashboard 
After login scroll down and click on get started button. This will navigate you to next page.
----------------------------------------------------------------------------------------------
2.	Creation of project.
Click on access API
Fill details
Click on submit and scroll down to get master info require for API.
After filling form you will get master details like receiver phone no #[A],code , barcode etc.
3.	Configuration.
Save sender no #(A) in client phone and send message(PROXY <Project_Name>).
This is subscription based method where each client needs to send PROXY <Project_Name> message to sender to subscript. (One time activity)  
Enter message and click send button. If recipient has subscribed mentioned above then will receive what’s app message. 
 
Development related stuff
To get API go to Developers -> API

This is the details you need to supply while creating RestRequest 
URL :
https://www.gupshup.io/developer/sms-api  

Code is commited in APIFile
