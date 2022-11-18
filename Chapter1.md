# Introduction

**Operating system** is the most fundamental system program.
- It controls all the computer's resources and provide a base upon which the application programs can be written.

![image](https://github.com/C0DER11101/OS_SelfStudy/blob/OS_SelfStudy/LayersOfOS.png?raw=true)

The hardware contains 3 levels **physical devices**, **microarchitecture**, and **machine language**.

### Physical Devices

> This is the lowest level that contains physical devices, consisting of integrated circuit chips, wires, opwer supplies, cathode ray tubes, etc, etc.....

### Microarchitecture
**Microarchitecture is the level where the physical devices are grouped together to form functional units.**

**This level contains some registers internal to the CPU and a data path containing an arithmetic logic unit.**

**Purpose of the _datapath_ is to execute some set of instructions.**


### Machine Language
**The hardware and the instructions form the ISA(Instruction Set Architecture). This level is called _machine language_.**

_Machine language typically has between 50 and 300 instructions, mostly moving data around the machine, doing arithmetic and comparing values._

**In this level, the I/O devices are controlled by loading values into special _device registers_.**


_The **main function** of the operating system is to hide all the complexity and give the programmer a more convenient set of instructions to work with._
