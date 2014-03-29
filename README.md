Storage Calculations for Messages
===

A simple set of javascript functions that help in capacity planning for hadoop or any other system that stores data.
You provide an input of the number of messages per second and the average byte size of the messages and you will see how much storage is required for

* Day
* Month
* Year

To execute:

* Clone the Git Repo
* Open a simple Http server
```
python -m SimpleHTTPServer 9999 
```
* Go to the url
```
http://servername:9999
```
