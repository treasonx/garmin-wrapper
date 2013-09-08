#Garmin API Wrapper

The Garmin Communicator plugin allows you to access your garmin devices from a
web browser. Any javascript developer can access the plugin and interact with
Garmin GPS devices. 

The Communicator plugin isn't very friendly to many modern JS environment and
depends on Prototype JS which is known to modify the global js environment. 

In order to allow modern application to cleanly interact with the Garmin plugin
this wrapper encapsulates the script in a same domain iframe and provides a
simplified API to interact with the Garmin devices. 
