# Display

## Why do we need it?

The display presents vehicle and engine information to the driver. It allows more information to be shown than would be possible using individual warning lights alone.

This helps the driver monitor the condition of the car and identify possible problems while driving. The design report notes that the driver interface on FTX6 was quite limited in the information it showed, so improving this was a big goal for FTX7.

## FTX7

FTX7 uses a five-inch dashboard display, listed in the [Electronics Overview](../../index.md) as a Raspberry Pi Touch 2 5" display. The display is controlled by the [Raspberry Pi](./raspberry-pi.md) and is connected to it using a ribbon cable.

The Raspberry Pi receives information from the ECU through a USB connection and is powered through a 12 V to 5 V converter. This allows ECU data to be processed and shown on the display.

As per the Electronics Overview, the main values shown on the display are:

- engine speed
- vehicle speed
- coolant temperature
- throttle position
- warning messages
- lambda target, actual and error
