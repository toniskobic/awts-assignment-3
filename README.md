# AWTS Assignment 3

AWTS Assignment 3 is a Java 17 Jakarta EE 9 Web system composed of a SOAP service and a Jakarta Server Faces application
for providing information about airports, locations and meteorological data made as part of a college assignment. 
The SOAP service sends requests to the OpenWeatherMap service and provides a WebSocket endpoint. 
Jakarta Server Faces application sends JAXWS calls to the SOAP service and sends requests to the LocationIQ service.

The project is set up so that it can be deployed to a Glassfish EE Server. SOAP service uses MySQL or HSQLDB for data management.

Project contains comprehensive documentation generated via Javadoc.

This assignment is the third of three assignments made as part of the faculty graduate studies course "Advanced Web Technologies and Services".

