# Dashed Lights Effect For LightBlender

Dashed Lights, generates a dashed format light in a range of LED strip.

![Simple Dashed Light](pics/LEDSimpleDash.gif "Simple Dashed Light")

**Note**: The motion toggles between two colors repeatedly. If you do not want this toggle you can set speed to zero.

## Parameters

There are a bunch of parameters for creating your desired Dashed effect. In this section, we will describe each parameter:

### LED Length

Determine length of the LED, You can set this value less and more than your real LED Length.

![LED Length 16](pics/LEDDashLedSize.gif "LED Length 16")
![Real LED Length 16](pics/RealLEDDashLedSize.gif "Real LED Length 16")

### First Section Length and Second Section Length

Determine the length of the sections of dashed line.

In this example we set 5 and 2 for sections respectively:

![section lengths](pics/realsecLen52.gif "section lengths")

### First Section Color And Second Section Color

These two parameters determine the colors for both sections.

In this example we used yellow and blue colors for sections:

![First Section Color And Second Section Color](pics/REALledCOLOR.gif "First Section Color And Second Section Color")

### Effect Start and Effect End

Determine the start and endpoints of the dashed line.

In gif below we limited effect start and effect end between 5 and 25:
![Effect Start and End](pics/realledsstartend525.gif "Effect Start and End")

### Speed

Determine the speed of shifting colors between sections.

**Note**: Set the value of this parameter to 0 to have a constant dash.

Here you can see some speed parameters examples:

Speed=0:
![Speed](pics/Realspeed00.gif "Speed")

Speed=100:
![Speed](pics/Realspeed100.gif "Speed")

Speed=300:
![Speed](pics/Realspeed300.gif "Speed")