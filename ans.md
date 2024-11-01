# Part 2
<!-- 
Suppose the following layout is used for the virtual addresses in a 64-bit system.
Directory: 20 Bits
Page Table: 20 Bits
Offset: 24 Bits -->

## (a) What is the total number of entries in the page directory?
## ANSWER: 2^(directory) = 2^(20) = 1,048,576 entries

## (b) What is the total number of entries in the page table?
## ANSWER: 2^(page table) = 2^(20) = 1,048,576 entries

## (c) What is the size of the page frames?
## ANSWER: 2^(offset) = 2^(24)bytes =  16MB

## (d) What is the max size of memory that can be allocated to a process?
## ANSWER: total bits of virtual memory = 20 + 20 + 24 = 64 bits  so 2^64 bytes is the max number of bytes that could be allocated to a process

