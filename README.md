# cmpe272-Extra-Assignment

ABSTRACT

Develop a smarter building prototype to detect air quality and noise level and send real time alert to occupants. Create and use virtual sensors to generate data http://virtualsensors.mybluemix.net/ 

PROJECT SUMMARY

Environment Alert is a simple and smart prototype that helps the occupants in getting notification about the environment that they are living in. The occupants of a house can use this prototype to detect the current readings of:
1.	Content of Carbon Dioxide in the air.
2.	Level of Noise Pollution. 
Once the maximum permissible level is configured, the occupants will get an email alert on their device saying that the maximum permissible level has been crossed with current reading of the virtual device and then the occupants can act accordingly. 

HOW TO USE

1. Virtual devices on bluemix must be set up.It is already set up in the code. You can create your own virtual device and use that credentials too.  
2. Create a node red starter application in bluemix platform 
3. Import the flow code provided in the repository to the current flow.
4. Configure the My Virtual Sensors module if you want to add your own virtual device id.
5. Add sender' and receiver's email id in the recipient nodes.
6. Deploy the application.