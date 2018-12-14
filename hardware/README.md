# HW status: your OPi will burn with flames!

## Hardware issues after manufacture

 * **MAJOR** There is a one short circuit between 5V and GND on USB connector shield
 * 3.5 AV connector placed upside down
 * Current shunt placed after USB, so current meter shows junk after USB power shut down
 * No filtering capacitors for temp and security devices

## What works

 * I2C works fine
 * USB works fine (data, power switching, power metering)

## What untested

 * ESD on USB
 * USB overcurrent indicator
 * UART + UART level shift
 * SPI
 * AV, Mic
 * PWM
