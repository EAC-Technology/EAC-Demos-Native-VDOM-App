# EAC-Demos-Native-VDOM-App
Here a VDOM App that implement some Demos of EAC Technology

Open project to understand implementation of EAC Applications

EAC means (Email Active Content), it's a technology provided by the company AppInMail (www.appinmail.io). 

This technology has 2 goals :
  - Attach a true identity to an email (The main identity is provided by AppInMail ID Server)
  - Encapsulate in a specific MIME code (text/wholexml) an abstract description of an User Interface with some endpoint to connect to a Business Logic.

This 2 points allows to create Email based applications called eApp, the email is a vector to transport the UI but it never excute anything. The execution of the eApp is done in client/server mode. The Business logic of the application can be done in any technology that can implement the specifications of EAC Technology.

This applications examples are built on VDOM Plateform :
  - To run VDOM Plateform go to : http://github.com/VDOMBoxGroup/vdomserver1.3

