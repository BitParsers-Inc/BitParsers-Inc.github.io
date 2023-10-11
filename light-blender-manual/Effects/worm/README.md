# Worm Effect User Manual

Worm Effect generates a worm like traveler on LED. It is very similar to the luminous traveler, but it shrink and expand like a worm.

## Parameters

To customize the way that effect runs, you can set the parameters as mentioned in below:

### Led Length

Determine the operational counts of LEDs. This can be less, equal or even more than your real count of LEDs.

### Worm Length

Determine maximum length of the worm effect (worm length in expanded state).

### Offset

This parameter specifies the starting for **JUST IN FIRST TRAVERSAL** of LED, and after exceeding the last available LED, it will use the first available LED to cross. This will help you to separate multiple luminous traveler effects when you are using light-blender to mix them together.

### Speed

Determines the travel speed of worm.

### Start Color, End Color, Gradient Algorithm

These two attributes work together to generate a gradient. If you see both `Start` and `End` colors the same (e.g., both yellow), you will see a solid color, like our other examples. But you can set them differently to achieve a gradient color.

There are two different `gradient algorithms` to generate these colors: Naive and Spectrum.

**Naive**: Use direct mixture of two colors to generate colors.

**Spectrum**: Use colors with wavelength between `start` and `end` colors to generate colors, like a part of a rainbow.

### Margin Start Length, Margin End Length, and Margin Disappear Severity

You can add fade-in/fadeout like margins in both sides (or just one side) of the gradient. This will help your effect to seem more smooth. `Margin Disappear Severity` is another parameter related to margins which helps you to adjust the severity of fading in/out.

### Worm Shrinkage Severity

This parameter determines how sever work shrinks in scale of 0 to 1.