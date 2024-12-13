## Add a button

Add a button to control the buzzer.

--- task ---

Add a Pin-Socket jumper wire to **GP21** and another Pin-Socket wire to a second **GND** pin.

![Buzzer wired to GP20 and GND and additional jumper wires connected to GP21 and GND.](images/buzzer-and-button.png)

--- /task ---

--- task ---

From the Raspberry Pi `Simple Electronics`{:class="block3extensions"} extension, add the following blocks to control your buzzer.

```blocks3
when button (21 v) [pressed v] ::extension hat
turn LED (20 v) [on v] ::extension

when button (21 v) [released v] ::extension hat
turn LED (20 v) [off v] ::extension
```

--- /task ---

--- task ---

Run your code and then touch the two M-F jumper wires together. The buzzer should sound. When you take them apart, the buzzer should stop.

--- /task ---
