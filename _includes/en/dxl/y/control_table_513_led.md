LED controls the indicator LED on the back of the servo.

| Value |  Description                                 |
| :---: | :------------------------------------------: |
| 0     | Turns off the LED at the back of the device. |
| 1     | Turns on the LED at the back of the device.  |


{% capture LED %}
**Note** : The LED also functions as an indicator displaying the device's current condition:

| Status        | LED Operation   |
|:-------------:|:---------------:|
| Boot-up       | Single blink    |
| Factory Reset | Four blinks     |
| Alarm         | Steady blinking |
|Bootloader Mode| Illuminated     |
{% endcapture %}

<div class="notice">{{ LED | markdownify }}</div>
