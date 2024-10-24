* Assuming that the in sensor.cs renode file we do not keep track of the reg that are being written by MCU, we only care about the reg that are being read by MCU so that we can pass the fuzz value to MCU via the reg being read. This won't work in cases if developer checks from the peripheral, by reading the value of the reg that was previously written by the MCU, and it exits or do not take the intended code path if the value mismatches. But as our goal is to fuzz the data being read by MCU , we might not care about the valid values that the MCU is looking for except in cases in which code do not proceed like invalid chip id, status, etc. for that we use config file with reg addr and corresponding value.


**Queries** : 
1. How to detect and skip delays()/while(1)/for(;;;) ?
2. How to decide when to exit (i.e. when 1st run finishes if no crash is detected) ?
3. How to process the input from the fuzzer , like getting `byte arr[]` from fuzzer, show to assign to different register, or should i fuzz the length of the data being fuzzed? 
4. Getting fw source code from previous research papers?
5. LibAFL slows down if it doesn't find any new path, is taht correct?
6. Problem with emulator/simulator vs actual code ?
7. how to see the impaxct on those peripherals
