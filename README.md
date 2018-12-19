# FurutaPendulum
Source and app files for the Furuta pendulum virtual and remote lab

# Installation and/or use requirements
To use the virtual lab app, only an up-to-date web browser is required.

To open and edit the source (.ejss) files, EjsS is required. EjsS can be downloaded for free from here: https://www.um.es/fem/EjsWiki/Main/Download

To use the remote lab app, the Quanser Furuta pendulum device (https://www.quanser.com/products/qube-servo-2/), LabView (http://www.ni.com/en-us/shop/labview.html), the LabView control program (available in the LV folder in this same repository), the LabView RIP server (https://github.com/UNEDLabs/rip-labview-server), a Moodle 3.1+ server (https://download.moodle.org/) and the EJSApp plugin (https://github.com/UNEDLabs/moodle-mod_ejsapp) are needed. All these things, except for the Quanser device and LabView, can be obtained for free.

For use and installation of each component, please visit their corresponding webpages.

# Use instructions
To use the Furuta pendulum virtual lab, follow these steps:
1. Download the ejss_virtual_furuta.zip file from this repository.
2. Extract the content to a folder.
3. Double click on the FurutaVirtualV3_Simulation.xhtml file.

To set up and use your own Furuta pendulum remote lab, follow these steps:
1. Download the LabView RIP server and the LabView control program (the furuta_vi.zip file) and install them in a computer with LabView 2014 or higher. This computer must be connected to the Quanser Furuta pendulum device.
2. Download the EJSApp plugin and install it in a Moodle server.
3. Download the ejss_remote_furuta.zip file and use it to add a new EJSApp activity in your Moodle server.
4. Access the newly created EJSApp activity in your Moodle course.
