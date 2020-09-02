.. AHU configuration User Guide documentation master file, created by
   sphinx-quickstart on Mon Aug 17 17:12:11 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

########################################
AHU Economizer Configuration User Guide:
########################################

Introduction
************

!!TEST DOC DELETE THIS WHEN DONE!!

AHU config tool

AHU Application Configuration
*****************************

The *AHU* Application behavior is controlled through these
configuration Pages:



Importing Master Driver Configuration Store
*******************************************
At the initial homepage, the user will be prompted to upload the **Master Driver** file. Values within the Master Driver Configuration Store will be parsed to provide options for Campus, Buidling, Device and Points throughout the application.

.. image:: _images/ahu_Frontpage.jpg

Once the user has selected the Master Driver Configuration Store, this homepage will not appear again. However, if the user needs to upload a different Master Driver Configuration Store at any point, this option can be accessed via the Menu icon in the top left of the application.

.. Warning:: Uploading a new Master Driver Configuration Store will remove all current data in the application.

.. image:: _images/master_Driver.jpg

After a *Master Driver* File is uploaded, there will be two new buttons that will appear 
as green below. 

Below The *Master Driver* button, there are two buttons that say:
*AHU File* and *Generate configuration file for...* The *Ahu File* will allow the user to submit a file that has been created by the AHU config 
previously, and the *Generate configuration file for...* will allow the user to create a new configuration file for either the *ECONOMIZER* or *AIRSIDE*. 

.. image:: _images/ahu_File.jpg

Economizer
**********

This section will go over all of the items that are located within the *Economizer* button located in the *Generate configuration file for...* 
button. 


When the Economizer is selected there will be a prompt to select *Campus*,
*Building*, and *Device*. These will all be selected as dropdown inputs. 

.. image:: _images/dropdowns.jpg

Point Mapping
*************
*Point Mapping* will be the first tab on the left side of the Economizer page. This will be 
located underneath the main configuration file and the *Default Economizer*. 

.. image:: _images/point_Mapping.jpg

Once *Point Mapping* is selected, configurations will show on the center of the screen. 


.. image:: _images/point_Config.jpg

Once the configuration is shown in the center of the screen, the dropdown inputs 
may be selected to configure. 

All of the *Point Mapping* configuration settings will be drop down inputs that are dependant Upon the 
main configuration file selected for the page. 

.. image:: _images/point_Populate.jpg

Settings
********

Settings is the second tab inside of the Ahu configuration Economizer section. 
Once settings is selected the center section will populate with configurations. 

.. image:: _images/settings.jpg

**Device Type**

*Device Type* will give you an option to either choose *AHU* or *RTU* underneath the settings 
title. 

.. image:: _images/device_Type.jpg

**Economizer Type**

Economizer type has two selections: *DDB* and *HL*.
Choosing one will provide specific configuration settings.

.. image:: _images/economizer_Type.jpg

Economizer Type: DDB
********************

**Data Window**

This selection will be an integer type ranging from 0 to 60 minutes. 
The user may input an integer or use the slider to obtain the number required.

.. image:: _images/data_Window.jpg

**Numbered Required Data**

This selection will be an integer type ranging from 0 to 20. 
The user may input an integer or use the slider to obtain the number required.

.. image:: _images/number_Data.jpg

**Desired Outdoor Air Fraction**

This selection will be an integer type ranging from 5 to 30. 
The user may input an integer or use the slider to obtain the number required.

.. image:: _images/desired_Outdoor.jpg

**Open Damper Time**

This selection will be an integer type ranging from 0 to 60 minutes. 
The user may input an integer or use the slider to obtain the number required.

.. image:: _images/open_Damper.jpg

**Minimum Damper Setpoint**

This selection will be an integer type ranging from 0 to 50 %. 
The user may input an integer or use the slider to obtain the number required.

.. image:: _images/minimum_Damp.jpg

**Rated Cubic Feet Per Minute**

This selection will be an integer type ranging from 0 to 6000 CFM. 
The user may input an integer or use the slider to obtain the number required.

.. image:: _images/rated_Min.jpg

**Energy Efficient Ratio**

This selection will be an integer type ranging from 1 to 15. 
The user may input an integer or use the slider to obtain the number required.

.. image:: _images/energy_Ratio.jpg

**Temperature Deadband**

This selection will be a floating point number ranging from 0.5 to 10. 
The user may also input a floating point number or use the slider to obtain the number required.

.. image:: _images/temperature_Dead.jpg

Economizer type: HL
*******************
The *Economizer* type *HL* will be the next selection. Once this option is selected, 
there will be new settings that the user may configure. 

.. image:: _images/econ_Typehl.jpg

**Economizer Switchover Setpoint**

This selection will be a integer number ranging from 0 to 20. 
The user may input an integer or use the slider to obtain the number required.

.. image:: _images/switch_Over.jpg

**Data window**

This selection will be a floating point number ranging from 0 to 60 minutes. 
The user may input an integer or use the slider to obtain the number required.
.. image:: _images/data_Win.jpg

**Number Required Data**

This selection will be a floating point number ranging from 0 to 60 minutes. 
The user may input an integer or use the slider to obtain the number required.

.. image:: _images/number_Req.jpg

**Desired Outdoor Air Fraction**

This selection will be a floating point number ranging from 5 to 30. 
The user may input a floating point number or use the slider to obtain the number required.

.. image:: _images/desire_Frac.jpg

**Open Damper Time**

This selection will be a floating point number ranging from 0 to 60 minutes. 
The user may input an integer or use the slider to obtain the number required.

.. image:: _images/damp_Time.jpg

**Minimum Damper Setpoint**

This selection will be a floating point number ranging from 0 to 50%. 
The user may input an integer or use the slider to obtain the number required.

.. image:: _images/min_Damp.jpg

**Rated Cubic Feet Per Minute**

This selection will be a floating point number ranging from 0 to 6000 CFM. 
The user may input an integer or use the slider to obtain the number required.

.. image:: _images/rated_Feet.jpg


**Energy Efficient Ratio**

This selection will be a floating point number ranging from 1 to 15. 
The user may input an integer or use the slider to obtain the number required.

.. image:: _images/energy_Ratio2.jpg

**Temperature Deadband**

This selection will be a floating point number ranging from 1 to 15. 
The user may input an integer or use the slider to obtain the number required.

.. image:: _images/Temp_Dead.jpg

Thresholds
**********

The last tab in the AHU config: Economizer is the *Threshold* tab. 

.. image:: _images/sidepanel.jpg

Once this tab is selected, there will be two options that appear on the center of the screen. 

.. image:: _images/thres_Select.jpg

If *Use Default thresholds** is selected, there will be no options to configure.

If *Customize Threshold Parameters* is selected, there will be new settings to configure. 

.. image:: _images/custom_Thres.jpg

**Low Supply Fan**

This selection will be a floating point number ranging from 0 to 100%. 
The user may input an integer or use the slider to obtain the number required.

.. image:: _images/low_Sup.jpg

**Mixed-Air Temperature Low**

This selection will be a floating point number ranging from 40 to 60 degrees. 
The user may input an integer or use the slider to obtain the number required.

.. image:: _images/Mix_Temp.jpg

**Mixed-Air Temperature High**

This selection will be a floating point number ranging from 80 to 90 degrees. 
The user may input an integer or use the slider to obtain the number required.

.. image:: _images/mix_Temp.jpg

**Outside-Air Temperature Low**

This selection will be a floating point number ranging from 20 to 40 degrees. 
The user may input an integer or use the slider to obtain the number required.

.. image:: _images/out_Low.jpg

**Outside-Air Temperature High**

This selection will be a floating point number ranging from 90 to 125 degrees. 
The user may input an integer or use the slider to obtain the number required.

.. image:: _images/out_High.jpg

**Return-Air Temperature Low**

This selection will be a floating point number ranging from 40 to 60 degrees. 
The user may input an integer or use the slider to obtain the number required.

.. image:: _images/return_Low.jpg

**Return-Air Temperature High**

This selection will be a floating point number ranging from 80 to 90 degrees. 
The user may input an integer or use the slider to obtain the number required.

.. image:: _images/return_High.jpg

**Temperature Difference Threshold**

This selection will be a floating point number ranging from 2 to 6. 
The user may input an integer or use the slider to obtain the number required.

.. image:: _images/temp_Diff.jpg

**Open Damper Threshold**

This selection will be a floating point number ranging from 60 to 90. 
The user may input an integer or use the slider to obtain the number required.

.. image:: _images/open_Damp.jpg

**OAF Temperature Threshold**

This selection will be a floating point number ranging from 5 to 15. 
The user may input an integer or use the slider to obtain the number required.

.. image:: _images/oaf.jpg

**Cooling enabled Threshold**

This selection will be a floating point number ranging from 5 to 50. 
The user may input an integer or use the slider to obtain the number required.

.. image:: _images/cooling_T.jpg

Json view
*********

.. toctree::
   :maxdepth: 2
   :caption: Contents: