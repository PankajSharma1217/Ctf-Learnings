![](https://i.imgur.com/Miug2LF.png)

![](https://i.imgur.com/Nrt4bT0.png)

![](https://i.imgur.com/0PznAwq.png)

So this challenge is based on Tar directory transversal vulnerbility.

This basically worked earlier in tar in linux in which 
if we tar a file named ../../../../xyzfile and if admin untar it  then it will overwrite it in the system.This vulnerbility was cleared up in tar in linux but 
it is still working in tarfile module of python.

tar -cPf a.tar server.py 

and make changes inside server.py defining current user="admin"

or   we can overwrite users.db at the server

