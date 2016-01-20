# Arduino-Serial-over-Ethernet

This code is meant to allow you to implement a way to remotely access your machines via serial, like a backdoor would like BASH over TCP using Netcat or Socat..

To use this script you will need an Arduino(with a USB serial connection such as the Arduino Uno or Arduino Mega) with an Arduino Ethernet shield and a network connection to the other Arduino(with a USB serial connection such as the Arduino Uno or Arduino Mega) with its own Ethernet shield.

This is a fork of the initial release version, so there are bugs and some limitations.
I am working on making the stock firmware/code more friendly to conventional serial communication software.

So far this is compatible with GtkTerm(more clients will be tested later..)
