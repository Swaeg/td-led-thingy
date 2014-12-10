td-led-thingy
=============

Send pixels to OpenPixelControl server for controlling addressable led strips with Fadecandy. Pixel data is generated in TouchDesigner.


Prerequisites
=============

Bunch of addressable led strips (the type?), a functioning power supply for powering the led strips and a Fadecandy controller with the led strips soldered accordingly. 

Included in /touchdesigner you can find the example TD patch that connects to the OPC server and sends the pixels.


TouchDesigner
=============

If you don't have TouchDesigner yet, get it from http://www.derivative.ca/. 

Once TouchDesigner is installed, copy opc.py to C:\Win\TD\thedir and restart(?) TouchDesigner.


Sample Patch
=============

In the included patch /touchdesigner/file.name you need to ...

[ScreenCaps]

and then

[ScreenCaps]

Don't press Play yet, you still need to fire up the Fadecandy server on the machine you have the Fadecandy´s usb cable attached to.


Fadecandy
=============
You need to start the Fadecandy server to receive the pixels from Touch Designer. Pre-compiled binaries are found in fadecandy/bin/. For Raspberry Pi use fcserver-rpi, OSX fcserver-osx and on Windows fcserver.exe.

Once started, you should see something like: "Fadecandy server listening at some.ip.address:7890". This means the server is up and running, waiting for a client to connect. Now head back to Touch Designer and press Play.




