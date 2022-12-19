# Decentralized-File-sharing-network

Synerzy:
 
I will be developing a peer to peer network based file sharing application(Android).
It is inspired from torrents and decentralization of internet.
 
 
High level Design:
For each and every network(peer to peer network) there is a central server.
The devices communicate with central server gets the meta data about other devices and communicate among themselves.
If a device wants to download a file
 It sends a request to central server.
The central server responds with meta data file.
 Based on the response, the transfer will be initiated.
After the central server update the metafile of this file. Hence, the network will be grown.

Meta File:-  Each file will have a metafile of it at central server.
Devices having this file will have the device ID.
By retrieving the device ID we can know the locality of the file in the device.
By having the meta file , with the help of socket programming the transfer can be Initiated and completed.
 
Why device-ID?
As IP addresses are assigned by DHCP service of ISP, they may change every time.        

Schema:- FID, metafile.txt
 
 
Features/Functionalities:-
I will be adding the functionalities of upload, download and search for files in the network.
The files are listed on a common list(central-list).
If an user want to upload the file using upload functionalities, the filename will be added to the central list.
Search for a file basically searches for the matching file using file name and search query.
Other functionalities include media player(audio and video).

#How to run:
Load the project into android studio
Establish the firebase connec tion
Run the application in Two different android devices
Now you will be able to upload or download the files that are mutually accepted.
