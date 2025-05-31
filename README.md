# Queue-Implementation-Using-Stacks\


Queue Implementation Using Stacks
Problem Statement
Design a FIFO queue using only standard stack operations with efficient time complexity.

Approach
Two-Stack Method:
input_stack: Handles all push operations (O(1))
output_stack: Reverses elements when needed for pop/peek (amortized O(1))
Lazy Reversal: Elements only transfer from input→output when output is empty

Complexity Analysis
Operation	Time	Space
Push	O(1)	O(n)
Pop/Peek	O(1)*	O(n)
Empty	O(1)	O(1)
*Amortized time
Key Insight
By reversing elements only when necessary, we maintain efficient average-case performance while strictly using stack primitives.

