## Assignment 1: Minions
>> *NOTE*: All commands to be executed from the project root folder only

To build the server do 
```
cd server
gcc server.c
cd ..
```
To build the client, do
```
cd client
gcc client.c
cd ..
```
For a demonstration of how everything works, start the server on one terminal
```
./server/a.out
```
And in another terminal
```
./client/a.out
```
On receiving a request, the server will parse the request, find what images are to be sent, zip them and send them as a single zip.
The client will receive the zip file, unzip it, save the images in 'client' folder, build the HTML file and open it in the preferred browser.