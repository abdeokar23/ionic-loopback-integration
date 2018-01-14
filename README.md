# Integrating Ionic and Loopback

The main idea behind this integration is to avoid the lengthy process of creating a REST API on Node JS.
Using this app we will add device parameters(device name, device type, device owner) to a NoSQL database, MongoDB to be specific. More such parameters can be added according to user requirements, with different customisations.

The Loopback Framework usage procedure can be found here:
https://github.com/strongloop/loopback-example-database

Another example for API creation using loopback can be found at:
https://opensourceforu.com/2017/07/building-rest-apis-loopback-framework/

Names used in this particular API, which are of significance and will be used for connecting loopback and ionic app are: deviceName, deviceType, deviceOwner. These names will be used when creating a loopback model, all of them are of type string, and have been set as required by default.

Change the port used by loopback according to your purpose, as the default port may/may not be occupied by other processes. You can do so by editing the config.json file in server folder under your loopback project folder. These changes should be enough to create a functioning REST API.

The ionic app can be found here:
https://github.com/abdeokar23/ionic-root
