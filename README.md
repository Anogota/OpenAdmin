1.There are three directories on the webserver. /artwork, sierra, and what else?
First what we need to do is turn on gobuster and check what's happend on the server, and what kind of directory are there.
And that how can see, there no many directory but we can see /music and this also answer for as question. 

![obraz](https://github.com/Anogota/OpenAdmin/assets/143951834/edc821c2-2422-4ae7-b8d7-efb9c1470eae)

2.On the page at /music, there is a link that doesn't point to another link on /music, but rather an administration tool. What is the relative path?
I did some recon manualy, checking the source code, but there i can't find anything, but when i go login, i found intresting directory /ona

![obraz](https://github.com/Anogota/OpenAdmin/assets/143951834/bb5c333d-8cd2-4493-848d-acee5b527cbd)

3.What is the version number of OpenNetAdmin that runs on the remote machine?
Also we can on above screan the version

4.If you exploit this instance to get code execution on the machine, in the context of what user is the execution happening?
