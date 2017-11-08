# dbus_src
D Bus code examples

### D Bus Links #####################
Explanation::
	1. http://opensourceforu.com/2009/03/d-bus-the-smart-simple-powerful-ipc/
	2. https://techbase.kde.org/Development/Tutorials/D-Bus/Introduction
	3. https://rm5248.com/d-bus-tutorial/
	4. http://www.matthew.ath.cx/misc/dbus
	5. http://maemo.org/maemo_training_material/maemo4.x/html/maemo_Platform_Development_Chinook/
	6. https://linoxide.com/how-tos/d-bus-ipc-mechanism-linux/ --> practical examples

Documentation::
	1. https://dbus.freedesktop.org/doc/dbus-tutorial.html
	2. https://www.freedesktop.org/wiki/Software/dbus/  -->  Contains links for other documentation

Introduction:
https://www.freedesktop.org/wiki/IntroductionToDBus/
https://pythonhosted.org/txdbus/dbus_overview.html --> decent explanation for dbus

Specification:
https://dbus.freedesktop.org/doc/dbus-specification.html

D Bus Sample Codes::
	1. https://github.com/fbuihuu/samples-dbus
	2. https://www.softprayog.in/programming/d-bus-tutorial

Extra links for reading:
https://electronicsforu.com/resources/software/a-guide-to-rogramming-in-perl-php-and-python
https://electronicsforu.com/electronics-projects/live-streaming-using-raspberry-pi
 
 
#### API Documentation ###########
	1. https://dbus.freedesktop.org/doc/api/libhtml/


****** Best Link for understanding basics of DBUS*********
https://pythonhosted.org/txdbus/dbus_overview.html

#### Installation ################## 
Development packages for DBUS
1.libdbus-1-dev --> dbus library and header files
2.libdbus-glib-1-dev --> glib and dbus binding library and header files 
 
#### Compiling Steps for dbus application ############### 
gcc dbus_client.c         -I/usr/include/dbus-1.0 \
				-I/usr/lib/x86_64-linux-gnu/dbus-1.0/include \
				-I/usr/include/glib-2.0 \
				-I/usr/lib/x86_64-linux-gnu/glib-2.0/include/ \
				-ldbus-1 \
				-ldbus-glib-1 \
				-Wall -Wextra
				
				
				
Notes::
--> Objects in D-Bus are uniquely identified through the combination of a 
	1. bus name,  -- uniquely identifies a client application connected to the bus
	2. object path -- uniquely identifies the object within that application

##Sequence of dbus hierachy of sub components
 Address -> [Bus Name] -> Path -> Interface -> Method
