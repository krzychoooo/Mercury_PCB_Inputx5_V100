# Mercury_PCB_Inputx5_V100   

<picture><img src="img/Input_V100.png" style="border: 4px solid grey"></picture>

Each input is isolated from the processor's power supply.   
Additionally, each input is isolated from other inputs.   
You can read the input state via the I2C bus.   
The module is powered by 3.3V.   
I2C transmission is provided by a PCF8574.   
You can set the module address using jumpers JP1, JP2, and JP3.   
<picture><img src="img/addresJumper.png" style="border: 4px solid grey"></picture>   
The PCF8574 chip can trigger interrupts.   
You can specify the GPIO line to which the interrupt will be connected using jumpers JP4, JP5, JP6, JP7, JP8, and JP9.   
<picture><img src="img/interrupt.png" style="border: 4px solid grey"></picture>   
<picture><img src="img/interruptSCH.png" style="border: 4px solid grey"></picture>   
