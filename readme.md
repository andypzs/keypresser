#Arduino hardware keyboard fuzzer

So, this is in escence a usb keyboard fuzzer.

This tool can be very helpfull when you need, for example, to test different key combinations. 

The scenario for this one is really easy.

In you computer, you will install the Serial TTL USB converter and you will open a serial terminal software like TeraTerm, Putty, Minicom, etc. and then, on that tool, you will select the port mapped by OS and set the speed to 1200bps, 8N1.

Then, you will flash your Arduino Pro Micro and then, connect the Arduino to the DUT.

No extra power is required. 

Once you plug everything, in your serial console you will see the message to start fuzzing.