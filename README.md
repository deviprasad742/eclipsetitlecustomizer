eclipsetitlecustomizer
======================

This plugin allows users to customize eclipse window titles. Very useful when working with multiple eclipse instances.

To use the plugin you can download the plugin from eclipsetitlecustomizer/etcupdatesite/plugins/ and add it to your eclipse instance.

After successfull installation the plugin creates a file named 'title.properties' which can be edited to change the 
format of the title.

The default format used is [$installName] - ($wsLocation) where the entries starting with $represent the keys which will 
be replaced progrmatically. 


Supported keys are 
#1.$installName-Name of the installation folder
#2.$wsLocation - location of workspace
#3.$wsName - name of workspace


Sampel Formats

Eclipse_Work - $wsLocation
Eclipse_Android - $wsName


