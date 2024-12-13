Qwiic_SerLCD_CircupBundle NOTE: CURRENTLY STILL IN DEVELOPMENT!
==============

<p align="center">
   <img src="https://cdn.sparkfun.com/assets/custom_pages/2/7/2/qwiic-logo-registered.jpg"  width=200>  
   <img src="https://www.python.org/static/community_logos/python-logo-master-v3-TM.png"  width=240>   
</p>
<p align="center">
	<a href="https://pypi.org/project/sparkfun-qwiic-serlcd/" alt="Package">
		<img src="https://img.shields.io/pypi/pyversions/sparkfun_qwiic_serlcd.svg" /></a>
	<a href="https://github.com/sparkfun/Qwiic_SerLCD_Py/issues" alt="Issues">
		<img src="https://img.shields.io/github/issues/sparkfun/Qwiic_SerLCD_Py.svg" /></a>
	<a href="https://qwiic-serlcd-py.readthedocs.io/en/latest/" alt="Documentation">
		<img src="https://readthedocs.org/projects/qwiic-serlcd-py/badge/?version=latest&style=flat" /></a>
	<a href="https://github.com/sparkfun/Qwiic_SerLCD_Py/blob/master/LICENSE" alt="License">
		<img src="https://img.shields.io/badge/license-MIT-blue.svg" /></a>
	<a href="https://twitter.com/intent/follow?screen_name=sparkfun">
        	<img src="https://img.shields.io/twitter/follow/sparkfun.svg?style=social&logo=twitter"
           	 alt="follow on Twitter"></a>
</p>

<table class="table table-hover table-striped table-bordered">
    <tr align="center">
        <td><a href="https://www.sparkfun.com/products/16396"><img src="https://cdn.sparkfun.com//assets/parts/1/5/1/2/2/16396-SparkFun_16x2_SerLCD_-_RGB_Backlight__Qwiic_-05.jpg" title="SparkFun SerLCD 16x2 - RGB Backlight (QWIIC)"></a></td>
        <td><a href="https://www.sparkfun.com/products/16397"><img src="https://cdn.sparkfun.com//assets/parts/1/5/1/2/3/16397-SparkFun_16x2_SerLCD_-_RGB_Backlight__Qwiic_-05.jpg" title="SparkFun SerLCD 16x2 - RGB Text (QWIIC)"></a></td>
        <td><a href="https://www.sparkfun.com/products/16398"><img src="https://cdn.sparkfun.com//assets/parts/1/5/1/2/4/16398-SparkFun_16x2_SerLCD_-_RGB_Backlight__Qwiic_-05.jpg" title="SparkFun SerLCD 20x2 - RGB Backlight (QWIIC)"></a></td>
    </tr>
    <tr align="center">
        <td><i><a href="https://www.sparkfun.com/products/16396">SparkFun SerLCD 16x2 - RGB Backlight (QWIIC)</a></i></td>
        <td><i><a href="https://www.sparkfun.com/products/16397">SparkFun SerLCD 16x2 - RGB Text (QWIIC)</a></i></td>
        <td><i><a href="https://www.sparkfun.com/products/16398">SparkFun SerLCD 20x2 - RGB Backlight (QWIIC)</a></i></td>
    </tr>
</table>

## Overview
This bundle provides the library [Qwiic_SerLCD_Py](https://github.com/sparkfun/Qwiic_SerLCD_Py): Python module for I2C control of the SparkFun Qwiic Serial LCDs.

This bundling repository is a hard fork of the [CircuitPython Community Bundle](https://github.com/adafruit/CircuitPython_Community_Bundle/tree/main/libraries) and uses their workflows to generate and release the bundle.

## Usage
Follow the instructions [here](https://learn.adafruit.com/keep-your-circuitpython-libraries-on-devices-up-to-date-with-circup/overview) to install circup. 

Next, pull down the latest version of the bundle published by this repository by executing the following in a command prompt: 

```circup bundle-add sparkfun/Qwiic_SerLCD_Circup_Bundle```

Finally, install the relevant library files to your device with: 

```circup install --py qwiic_serlcd```

## Updating
To update this bundle:

1) Publish a release/tag in the [Qwiic_SerLCD_Py](https://github.com/sparkfun/Qwiic_SerLCD_Py) repo. 
2) Manually update the necessary library submoudules of this repository to point to that new tag, or run the update-submodules.sh locally and then push to this repository. 
3) Create a new tag/release for this repository. This will trigger a workflow to publish the necessary circup artifacts.

## Building
This bundle will be automatically built and released by GithHub workflows when a new tag is created in this repo.
