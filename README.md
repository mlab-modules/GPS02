<!--- PrjInfo ---> <!--- Please remove this line after manually editing --->
<!--- 00a56be08b96043df9e37d6aff7b6990 --->
<!--- Created:2020-06-01 14:57:55.686464: ---> 
<!--- Author:: ---> 
<!--- AuthorEmail:: ---> 
<!--- Tags:: ---> 
<!--- Ust:: ---> 
<!--- Label --->
<!--- ELabel --->

<!--- Name:GPS02B: --->
# GPS02B - RTK navigation capable GPS module

<!--- LongName --->
<!--- ELongName ---> 

<!--- Lead --->
GPS02B is a high-precision GNSS reciever that can accurately determine the user's location, speed, and direction using signals from multiple satellites. Reciever supports of RTK (Real time kinematics) technology with which you can achieve very high accuracy. GPS02B reciever is based on u-blox [NEO-M8P](https://www.u-blox.com/en/product/neo-m8p-series) reciever. 

<!--- ELead ---> 

Thanks to the built-in USB-B connector, the module can be used directly with a computer as a GNSS receiver. For example, using GPSD software equipment. If you need to use receiver in a larger device, you can use the signals on the pin-headers. There, you will find NMEA/UBX serial output, I2C for access to the u-blox module, and signals indicating the receiver's status (PPS, FIX, ...). The receiver can be configured over USB using the u-center tool.

The receiver is not equipped with an integrated GNSS antenna. An external GNSS antenna can be connected to the receiver via an MCX connector, and a jumper can be used to select whether the connected antenna is active.

The receiver can be powered in several ways. It can be powered via USB, with the integrated regulator providing the required 3.3V for the u-blox module to operate. If external power is required, the receiver can be powered through a header pin, where either 5V or 3.3V can be supplied. Configuration is done using jumpers. Module is equipped with a backup capacitor for short-term power loss and keeping of satellite data in the receiver's memory.

![GPS02A](doc/img/GPS02A_top.jpg) 

## Antennas
> TODO

## Usages

#### Standalone USB GPS reciever

#### GPS reciever with serial (NMEA) output

#### Signal time marking

#### PPS provider for time sync


<!--- Description --->
<!--- EDescription --->
<!--- Content --->
<!--- EContent --->
<sub><sup> Generated with [MLABweb](https://github.com/MLAB-project/MLABweb). (2020-06-01)</sup></sub>
