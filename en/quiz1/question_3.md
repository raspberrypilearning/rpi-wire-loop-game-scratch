--- question ---

---
legend: Question 3 of 3
---

Which of the following blocks, would lower a score by 1, each time a button is pressed?

--- choices ---

- (x) 1: 
```blocks3
when button (21 v) is [pressed v] ::extension hat
change [score v] by (-1)
```

--- feedback ---

Correct. The score is changed by `-1`, so it goes down by one each time the button is pressed.

--- /feedback ---

- ( ) 2: 
```blocks3
when button (21 v) is [pressed v] ::extension hat
change [score v] by (1)
```

--- feedback ---

No. This would increase the score, each time the button is pressed.

--- /feedback ---

- ( ) 3: 
```blocks3
when button (21 v) is [pressed v] ::extension hat
set [score v] to (1)
```

--- feedback ---

No. This would set the score to a value of 1, so the score would then never change.

--- /feedback ---

- ( ) 4: 
```blocks3
when button (21 v) is [released v] ::extension hat
change [score v] by (1)
```

--- feedback ---

No. This would increase the score, each time the button is released.

--- /feedback ---

--- /choices ---

--- /question ---