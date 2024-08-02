
Udo Möller's description:

M32632 Overview

The M32632 is an FPGA implementation of the Series 32000 architecture. The design is compatible to the NS32532 CPU and the NS32381 FPU. This will guarantee that existing software is running without modifications. The performance will be higher than the origin.

National Semiconductor never build a NS32632. In Spring 2011 I asked National whether they have a problem with the name and they said "please don't use the NS in front". I choosed "M" for some reasons and the M32632 was born.

In June 2015 the M32632 version 1.0 was released at www.opencores.org after nearly six years of development. One year later in August 2016 the version 2.0 was released. Many unexpected bug fixes were necessary and a change in architecture improved the clock speed. The table below compares some key characteristics of the M32632 V2 with the NS32532.

| Feature                         | NS32532            | M32632 V2          |
| ------------------------------- | ------------------ | ------------------ |
| Clock Freq                      | 30 MHz max         | 30 MHz max         |
| Basic Instruction Cycle Count   | 2                  | 1                  |
| Data Cache Size                 | 1024 bytes         | 8192 bytes         | 
| Data Cache Associativity        | two way            | two way            |
| Instruction Cache Size          | 512 bytes          | 8192 bytes         |
| Instruction Cache Associativity | direct mapped      | two way            |
| TLB Size	                      | 64 entries         | 2 * 256 entries    |
| TLB Associativity	              | fully associative  | direct mapped      |
| FPU	NS32381	integrated          | integrated         | integrated         |


See http://www.cpu-ns32k.net/ for more information
