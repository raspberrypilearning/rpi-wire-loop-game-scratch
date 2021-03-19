--- question ---

---
legend: Question 2 of 3
---

Which of the following blocks, would sound a buzzer on pin 20, when a button on pin 21 is pressed? 

--- choices ---

- ( ) 1: 
```blocks3 
when Button (21 v) [released  v] ::extension hat
turn LED (20) on
```

--- feedback ---

No. This would turn on a buzzer on pin 21 when the button is released.

--- /feedback ---

- ( ) 2: 
```blocks3 
when Button (20 v) [pressed  v] ::extension hat
turn LED (21) on
```

--- feedback ---

No. This would turn on a buzzer on pin 21 when a button on pin 20 is pressed

--- /feedback ---

- ( ) 3: 
```blocks3 
when Button (21 v) [pressed  v] ::extension hat
turn LED (21) on
```

--- feedback ---

No. This code tries to use the same pin for the buzzer and the button.

--- /feedback ---

- (x) 4: 
```blocks3 
when Button (21 v) [pressed  v] ::extension hat
turn LED (20) on
```

--- feedback ---

Well donw. This would turn on the buzzer when the button on pin 21 is pressed.

--- /feedback ---

--- /choices ---

--- /question ---