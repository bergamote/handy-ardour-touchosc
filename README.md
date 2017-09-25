# Handy Ardour-TouchOSC

A phone-sized layout to control **Ardour** with **TouchOSC** based on [1channel-phn][link] by Len Ovens

![Screenshot][screenshot]

## Instructions:

*Following are the instructions from 1channel-phn.*

turn on OSC in Ardour in perferences->ControlSurfaces  
open the settings GUI  
Set Port Mode to Manual, port of 8000 is fine (hit enter after setting)  
Set Bank Size to 1 (hit enter after setting)  
Set Gain Mode to Position  
In the Default Strip Types tab:  
	check all lines from the top to Master (there is no dedicated master strip)  
	The Strip Types Value will = 191 if this is correct.  
	(the user is free to ommit any of the tracks types from the list above)  
Back in the OSC Setup tab select the Clear OSC Devices button  
	(This is generally not needed, but if you have tried to send OSC messages from  
	your phone before, this will clear anything remembered from that)  
  
Install TouchOSC on your phone if it is not already installed.  
run/open touchOSC:  
set the ip address to the IP of the computer running Ardour  
set the send port to 3819  
set the receive port to 8000  
download the accompanying file to your tablet and find it with touchOSC and load it.  
it should display vertically.    
In the top right corner touch the connect button.  

## Controls:

The upper half of the screen shows the controls for the currently selected track. The previous or next track can be selected with the up and down keys.  
The lower half of the screen shows the time and transport controls.

Most buttons and faders should be self-explanatory.
  - The center of the record button lights up if any track is record-enabled.
  - The dotted circle below the record button is the `Forget` button from *1channel-phn*. Pressing it stops the current recording without saving it.
  - You can see if any track is set to solo and un-solo all of them using the `solo` led in the top right.
  - **Important** You might need to press `Connect` every now and then to refresh the values displayed.
  

[link]: https://github.com/ovenwerks/ardour-touchOSC/tree/master/1channel-phn
[screenshot]: screenshot.jpg

