
The most standard questions are "volatile", "restrict", "register", "extern" keywords, memory model, interrupts, error handling and interprocessor communications 

callback functions

circular buffer implementation
RTOS
OOP concepts
array manipulation
leetcode concurrency
Interrupts
drivers
writing OS task scheduler
Debugging
Zephyr
solve a problem with a singly linked-list in C code

*****  basic algorithms: selection sort, exchange sort, quicksort, heapsort or mergesort, use of lists, stacks, (priority) queues, trees and tries; but graphs are even more important: depth first traversal, breadth first, Kruskal, Prim. 
Big O analysis 

“Cracking the Coding Interview” is a particularly good book written by someone who used to do these interviews at Google and still follows much the same style at CareerCup 

for firmware/embedded code, bit-twiddling challenges are more relevant, so expect Fascicle 0 and 1 of Vol 4 of Knuth’s “The Art of Computer Programming” to cover the kinds of algorithms you are more likely to be quizzed about.

https://xlinux.nist.gov/dads/ 

https://github.com/omkarvyas/Learning/tree/master/IV 


## C notes 

1. **Two sum using hashmap in c** Since the range of possible values for `nums[i]` and `target` is from −10^9−10^9 , a simple array-based hash map won't be feasible due to memory limitations. Instead, we can use a dynamically allocated hash map with a linked list to handle collisions. 
2. **Two sum using hashmap in c** : **Hash Function**: The hash function maps each number to a positive index using the modulo operator with a large prime number (`100003`). This helps reduce collisions and allows for better distribution of values in the hash map.
3. in C, the result of the modulo operation takes the sign of the dividend (the first operand).
### Week 1: Core Concepts & Embedded Coding Practice

|Day|Focus Area|Tasks|Time (hrs)|
|---|---|---|---|
|Day 1|Embedded System Architecture|Revise microcontroller architecture (ARM, RISC-V), peripherals, GPIO, timers|3|
|Day 2|Firmware Concepts|Study firmware development (memory management, interrupts, RTOS basics)|3|
|Day 3|Coding Practice (C/C++)|Solve basic LeetCode problems: arrays, strings, linked lists|2|
|Day 4|Embedded Projects|Use TI MSP432P4: Implement GPIO control, timers|3|
|Day 5|Data Structures & Algorithms|Practice queues, stacks, and linked lists problems in C++|2|
|Day 6|Debugging and Profiling|Review debugging tools (GDB, JTAG) and techniques for embedded systems|3|
|Day 7|System Design Basics|Study low-power designs, resource-constrained system design|3|

### Week 2: Advanced Concepts & System Design

|Day|Focus Area|Tasks|Time (hrs)|
|---|---|---|---|
|Day 8|Communication Protocols|Review I2C, SPI, UART; practice implementation|3|
|Day 9|Memory Management & Bit Manipulation|Practice problems related to pointers, bit manipulation|2|
|Day 10|Coding Practice|Continue LeetCode problems (dynamic programming, recursion)|2|
|Day 11|Firmware Optimization|Study optimizing firmware for power, memory, performance|3|
|Day 12|System Design (Embedded Focus)|Practice design questions involving embedded trade-offs|3|
|Day 13|Hands-on Firmware Development|Implement an I2C or SPI driver on TI MSP432P4|3|
|Day 14|Coding & Debugging|Solve 2-3 LeetCode hard problems + debugging session|3|

### Week 3: Mock Interviews & Project Revision

|Day|Focus Area|Tasks|Time (hrs)|
|---|---|---|---|
|Day 15|Whiteboard Practice|Simulate mock interviews: solve problems on whiteboard|2|
|Day 16|PhD Project Review|Prepare to explain research work, technical depth, impact|2|
|Day 17|Embedded System Projects|Build a more complex firmware project: multitasking or RTOS|3|
|Day 18|System Design Interview Practice|Practice 2-3 system design questions with embedded focus|3|
|Day 19|Mock Interviews|Conduct a mock interview with a friend or peer|2|
|Day 20|Review & Relax|Light revision of key concepts; take a break for the day|1-2|

### Week 4: Final Preparation (3-4 Days)

|Day|Focus Area|Tasks|Time (hrs)|
|---|---|---|---|
|Day 21|Final Mock Interviews|Run through another coding and system design interview|2|
|Day 22|Problem Solving & Debugging|Last review of difficult problems, debugging, and coding|2|
|Day 23|Interview Warm-up|Light review + get in a good mindset for your interview|1-2|