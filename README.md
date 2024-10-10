# Arduino-EEPROM-Build-Docs

High-quality distribution of embedded systems requires disciplined tracking of:
1. Hardware Model Numbers
2. Hardware Serial Numbers
3. Software Version Numbers
4. Hardware Calibration Constants.

This project is an attempt to standardize (and thus encourage) the use of this information, 
by both documentation and possibly by creating a very small Arduino Library that puts this in code and makes it easier
to use.

Most Arduino-style systems have an EEPROM or similar static memory, which is appropriate for this information.
Having a standardized library that uses these different permanent memory systems would make development on 
different platforms usable.

An example Arduino script that includes and uses this library might be quite useful.
