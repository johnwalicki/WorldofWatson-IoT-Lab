# WorldofWatson-IoT-Lab
Introduction to IoT: Build Your Own Basic IoT App
World of Watson Hands-On Workshop

Download this PDF and Node-RED flows at : https://github.com/johnwalicki/WorldofWatson-IoT-Lab

Author: 
John Walicki	| walicki@us.ibm.com 		| @johnwalicki

Topics covered: Raspberry Pi, Node-RED, Watson Internet of Things Platform, Cloudant NoSQL Database, Twitter, Twilio, and Weather Company Data for IBM Bluemix.

In this lab, we will unbox and set up a Raspberry Pi and Raspberry Pi SenseHat and connect to the IBM Bluemix and Watson IoT Platform.   We will query the temperature via the SenseHat and send data to the Watson IoT platform.  Watson IoT Platform will monitor the temperature and alert maintenance of a high temperature. Using Node-RED, running on the Raspberry Pi and in Bluemix, the application will read the temperature value from a SenseHat. If the temperature rises, a LED light is turned on. The temperature will be sent via Watson’s Internet of Things Platform service to a Node-RED application hosted on IBM Bluemix. If the SenseHAT experiences excessive acceleration shocks, we’ll send a tweet via Twitter. We will retrieve outside weather data and display it on a LED screen connected to the SenseHat. We’ll store acceleration shocks in a Cloudant NoSQL database so we can track patterns. Finally, we’ll create an HTTP endpoint that exposes the historical acceleration shocks that third-party applications could consume and perform analysis or other fun stuff. 
