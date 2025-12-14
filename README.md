# ADC Utils

Utility functions for calculating voltages from ADC values.

## ADC Value to Voltage

https://learn.sparkfun.com/tutorials/analog-to-digital-conversion/all

Formula:

```
ADC Resolution     ADC Reading 
-------------- = --------------
System Voltage   Analog Voltage
```

When running on a micocontroller, you should know everything except the analog voltage.

## Voltage Divider calculation

Formula:

```
       Vsource * R2
Vout = ------------
        (R1 + R2)  
```

Calculate `Vsource` given the read voltage and the resistor values.

## Using this code

Copy the header and c file into your project

## License

MIT
