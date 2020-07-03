# RotaryEncoder Library

A library for the Arduino environment for using a rotary encoder as an input.

I was searching a library for using a rotary encoder in my latest project and found a lot of information on this topic but none of the existing libraries did immediately match my expectations so I finally built my own. 

It supports the type of rotary encoder that has a phase change on both input signals when rotating one `notch`.

The article on my web site explains the software mechanisms used in detail so you can understand
the coding and might be able to adjust it to your needs if you like:

<http://www.mathertel.de/Arduino/RotaryEncoderLibrary.aspx>

Modified by **ShaggyDog18@gmail.com**

## Change Log

Introduced two new rotation directions detecting fast encoder rotation (still modification is 100% backward compatible with the original library): 
- `FCCW` - Fast Counterclockwise
- `FCW`  - Fast Clockwise
