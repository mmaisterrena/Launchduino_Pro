# Launchduino Pro
__________
Use Arduino Uno (or Mega) and the USB Host Shield to transform your Novation Launchpad S into a stand-alone (no need for a computer) midi "keyboard" similar to Ableton's Push instrument mode. 

Developed by Mauricio Maisterrena.
  
# Requirements:
 
-Hardware:
 * Novation Launchpad S (haven't tested other version but it might work as well on the original and the RGB versions)
 * Arduino Uno or Mega
 * Arduino USB Host Shields from Circuitsathome.com (or replica)
 * Female MIDI jack
 * 220 ohm resistor
 * Wires 
  
 
-Software:
 * Arduino MIDI library
   http://playground.arduino.cc/Main/MIDILibrary
  
 * for use with USB Host Shield 2.0 from Circuitsathome.com
   https://github.com/felis/USB_Host_Shield_2.0
 
 * Yuuichi Akagawa's USB MIDI library
   https://github.com/YuuichiAkagawa/USBH_MIDI

# How to Connect
* Plug the USB Host Shield to your Arduino .
* To send the midi from the Arduino follow the diagram shown in this page https://www.arduino.cc/en/Tutorial/Midi
* Install the libraries mentioned on the requirements secction by followinng the instructions in this page http://arduino.cc/en/Guide/Libraries 
* Upload the Launchduino Pro File tio your Arduino.
* Connect your Lauchpad to the USB Host Shield.
* Have fun.

# Features
 * Send Midi notes using Launchpad S grid.
 * 5 Diferent Scales to choose from (Mayor, Minor, Flamenco, Blues, Chromatic) plus a Drum set.
 * Leds display the root notes (yellow) ant fifths (green) of the selected scale.
 * Octave up and down buttons.
 * Change the root note of the selected scale by presing a button.
 * Send midi to 3 diffecrent midi channels plus an additional channel for drums.
 * Change midi channel just by pressing the corresponding button.
 * Midi Panic Button.
 
# Funcionality Cheat Sheet

(1) (2) (3) (4) (5) (6) (7) (8)       
[_] [_] [_] [_] [_] [_] [_] [_] [9] 
[_] [_] [_] [_] [_] [_] [_] [_] [10]
[_] [_] [_] [_] [_] [_] [_] [_] [11]
[_] [_] [_] [_] [_] [_] [_] [_] [12]
[_] [_] [_] [_] [_] [_] [_] [_] [13]
[_] [_] [_] [_] [_] [_] [_] [_] [14] 
[_] [_] [_] [_] [_] [_] [_] [_] [15]
[_] [_] [_] [_] [_] [_] [_] [_] [16] 

*Horizontal row of circle pads

1) Octave Up.

2) Octave Down.

3) Root Note Previous Note (of the chromatic scale).

4) Root Note Next Note(of the chromatic scale).
 
5) Midi Channel 10
 
6) Midi Channel 11
 
7) Midi Channel 12
 
8) Midi Panic (Turn off all sounding notes)



<br>
*Vertical column of circle pads

-Scale Selection

 9) Mayor
  
10) Minor
 
11) Flamenco

12) Blues

13) Chromatic


14) Drum Pads (Midi Channel 16)



# Donate

Help yourself by helping us support you! Many hours have been spent developing this code. Since you find it useful, please consider donating via the button below.

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=NRH7682YRXFP2"><img src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif" alt="PayPal - The safer, easier way to pay online!" /></a>

