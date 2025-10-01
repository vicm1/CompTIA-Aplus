What is memory?
Random Access Memory (RAM) is the most common
But it’s not the only kind of memory

RAM is not referring to hard drive or SSD storage
Data is stored permanently on the drive

Data and programs can only be used when moved to RAM

RAM(Random Access Memory) Slots
Memory types have changed through the years
Driven by standardization and technology

One of the most important components of your computer
Speed, Speed, Speed


Every motherboard is different
Check your documentation

DIMM
DMM
Dual inline memory module
Electrical contacts are different on each side

64 bit data width

Separation in the middle
Different for every DDR
DDR4 has different DIMMs lined up compared to DDR1

SO-DIMM
Small outline dual in-line memory module
About half the width as a DIMM

Used in laptops and mobile devices


Goes in horizontal with the motherboard


Dynamic Random Access Memory

These individual chips are the memory installed on the DIMM
The memory on the DIMM
Dynamic
Needs constant refreshing
Without refreshing, the data in the memory dissapears

Random Access
Any storage locaction can be accessed directly
Can access any data on any of these chips any time, don’t have to fast forward or rewind like magnetic tape
Unlike magnetic tapes

SDRAM
Synchronous DRAM (SDRAM)
SDRAM is synchronous with the common system clock
Queue up one process while waiting for another
Classic DRAM didn’t wait for a clock signal
Having a clock allows many of the components to keep track the standard rate of data being transferred back and form

SDR vs DDR

DDR = Double Data Rate, can transfer information at the top and at the bottom of the clock cycle, doubling from SDR

Double Data Rate 3 (DDR3) SDRAM
Twice the data rate of DDR2
Larger chip capacities

No backwards compatibility
Speed brings sacrifice

Double Data Rate 4 (DDR4) SDRAM
Speed increases over DDR3
Faster frequencies

Again, no backwards compatibility

Double Data Rate 5 (DDR5) SDRAM
Faster data transfers between the memory module and motherboard
Higher speeds than DDR4

 The key has moved
No backwards compatibility




Memory Technologies
Memory that checks itself
Used on critical computer systems
VM servers, database servers, any server

Parity memory
Adds an additional parity bit for each byte stored in the memory
Won’t always detect an error
Can’t correct an error
But it can tell your a memory error has occurred, might need a reboot

Error Correction Code (ECC) - if memory error was noticed
Detects errors and corrects on the fly
Not all systems use ECC
It looks the same as non-ECC memory

Parity
Even Parity
The parity bit makes an even number

Even so the parity is 0 so it can stay even
Odd so the parity is needed to be 1 so it can be even
Odd so the parity bit needs to be 1 so it can become even

 When we retrieve this information from memory, we perform our own parity bit check and then compare that parity bit to the one that was stored in memory
If identical then that particaul byte is intact and no errors

Parity
Valid or error?
Even parity byte


Row 1: correct parity bit is 1 to make even
Row 2: Incorrect, should be 1 instead not 0 to make it even, if it’s 0 it stays odd
Row 3: Correct, parity bit is 1 to make it even

CPU to RAM throughput
There’s a maximum throughput between RAM and CPU
The memory bandwidth

Measured in MT/s
Megatransfers/s
Million transfers per second
ex) 32 GB DDR5, 1x32GB, 5600MT/s

Faster is better
Physics becomes a challenge

Multi-channel memory
Difficult to increase the speed
Push as much as possible across a single memory bus
Two memory modules are faster than one


Add channel to increases throughput

Multi-channel memory
Dual-channel, triple-channel, or quad-channel
Memory combinations should match
Exact matches are best

Memory module slots are often colored differently



Storage Devices
Need some way to store information when the computer is off
RAM requires power to maintain the data (Volatile)

Many different ways to store data (non volatile)
Hard drives
Solid-state drives
Flash drives
Memory cards
Optical drives
