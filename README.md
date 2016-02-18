# Mooshimeter-PythonAPI

A python API relying on the BLED112 to talk to the Mooshimeter


## Setup / Dependencies:
 - Python 2.X
 - pyserial
 
   ```
   python -m pip install pyserial
   ```
    
- bglib
  1) Get the **bglib.py** file from **https://github.com/jrowberg/bglib/tree/master/Python**
  2) Copy **bglib.py** to EITHER
    - this folder
    - in your Python Lib directory (usually C:/PythonXX/Lib)



## Example.py:
This script is meant to demonstrate use of the Mooshimeter and BGWrapper classes.
The script does the following:
- Scan for BLE devices
- Filter for Mooshimeters
- Connect to the Mooshimeter with strongest signal
- Configure the meter to read Voltage in 60V range and Current in 10A range
- Begin streaming data and printing the results to the console
  - aser1
  - aser1