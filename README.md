Launchdino_Pro
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
  
 
-SoftWare:
 * Arduino MIDI library
   http://playground.arduino.cc/Main/MIDILibrary
  
 * for use with USB Host Shield 2.0 from Circuitsathome.com
   https://github.com/felis/USB_Host_Shield_2.0
 
 * Yuuichi Akagawa's USB MIDI library
   https://github.com/YuuichiAkagawa/USBH_MIDI

# How to Connect
Just plug the USB Host Shield to your Arduino and follow the diagram shown in this page https://www.arduino.cc/en/Tutorial/Midi

# Features
 * Send Midi notes using Launchpad S grid.
 * 5 Diferent Scales to choose from (Mayor, Minor, Flamenco, Blues, Chromatic) plus a Drum set.
 * Leds display the root notes (yellow) ant fifths (green) of the selected scale.
 * Octave up and down buttons.
 * Change the root note of the selected scale by presing a button.
 * Send midi to 3 diffecrent midi channels plus an additional channel for drums
 * Change midi channel just by pressing the corresponding button.
 * Midi Panic Button

# Donate

Help yourself by helping us support you! Many hours have been spent developing this code. Since you find it useful, please consider donating via the button below.

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=NRH7682YRXFP2"><img src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif" alt="PayPal - The safer, easier way to pay online!" /></a>

