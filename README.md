# AnanyaDockerLaha1234-
3-tier architecture using Docker-compose
Name of the service is Fe which stands for front end for setting up front end.
It has to pull and contain an image. Port mapping is followed by the network it has to use when it is 
installed on the local machine. 
The second micro service is Mongodb. The container name, the image, network are provided. 
Volumes is being used because even if Mongodb container terminates the data should be persistent and the third micro service is API which is built using spring boot.
A volume is created for Mongodb a data stored in MongoDB as said before.
All these applications should run on a single network so a network is also declared which creates Java home app network using bridge driver.
So this is a compost file. 
If this multi-tier application needs to be set up, we need to compose the file properly.
It created a network and it has created three containers using three different images.

