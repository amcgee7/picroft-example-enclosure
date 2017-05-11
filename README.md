# picroft-example-enclosure
This is a demonstration enclosure for picroft

## Files

 - __init__.py: Just makes this a module.
 - README.md: This document
 - enclosure_interface.py: This is a base class for new custom enclosures
   to start from.
 - picroft.py: The sample enclosure that just logs to the screen
 - picroft_test.py: This will test an enclosure

## Requirements

This enclosure requires a working install of mycroft-core and that the
messagebus be running while the enclosure is running.

## Usage

1. Mycroft service should be running
2. Enable the mycroft virtual enviroment.
3. Clone this code.
4. From the code base run ```python ./picroft.py``` this will start the enclosure.
5. Create a nother terminal from within the same code base
6. Enable the mycroft virtual enviroment for the new shell.
7. run ```python ./picroft_test.py``` this will test the enclosure

Log messages should appear in the enclosure's terminal that shows the
messages are received.

