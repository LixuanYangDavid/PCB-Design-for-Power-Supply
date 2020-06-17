# PCB-Design-for-Power-Supply

Hi there,

This is a PCB Design that aims to manufacture a Digital Power Supply(DPS) which should be working in Antartica.

1. The DPS shall not suffer damage at temps down to -40°C to ensure the DPS is still working in an extreme environment in Antarctica.  
2. The DPS shall maintain voltage output specifications over the temperature range of 0~70°C.
3. There shall be only one input voltage (0v-30v provided by a bench-top power supply) to operate the DPS and two outputs voltage (5V and 12V). As for the input voltage, it cannot be close to 5V and 12V (+/- 10%). Therefore, any input voltage in the range of 4.5V-5.5V and 10.8V-13.2V are not acceptable.  
5. The DPS shall have a 5 V output to drive sensors, CPU, and RAM (according to Table 2). In Table 2, the minimum value of the required voltage should be 4.85V and maximum value should be 5.15V. Thus, the 5V output shall maintain from 4.85V to 5.15V. Any values beyond this range could damage components. The current load of 5V shall have a maximum value of 20mA.
6. The DPS shall have a 12 V output to drive FLASH memory only (according to Table 2). From Table 2, the Required voltage for FLASH memory is from 11.2V to 12.8V, which means the 12V output shall maintain from 11.2V to 12.8V. Also, a maximum 20 mA current load should be maintained.
7. The DPS shall have a power efficiency greater than 60% with 20 mA current load on either of the two outputs.
8. The DPS shall maintain voltage output specifications with an input voltage +/-20% from nominal.
9. The DPS shall have a mass of no more than 25 g including PCB and components (without leads), to minimise the weight of the system. 
10. The DPS shall generate maximum 30 mA output current under a short circuit condition on either output. It aims to protect the system when the emergency occurs. 
11. The DPS shall minimize the power consumption from the battery for maximum lifespan for at least 15 years.
