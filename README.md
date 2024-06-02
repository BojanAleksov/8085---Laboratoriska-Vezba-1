# 8085---Laboratoriska-Vezba-1
Да се напише еквивалентна асемблерска програма на соодветната програма
напишана во виш програмски јазик. 
```
#define N 30
void main()
{
 int x[50], y[50], z[50];
 for (int i=1; i<=N; i++)
 {
 z[i]=10;
 x[i]=4*y[i];
 }
}
```

**Developed by:**

[Bojan Aleksov](https://github.com/BojanAleksov)


**Subject**

Microcomputer's systems

**Built With**

This project is built using the following tools:

- [8085 simulator](https://github.com/8085simulator/8085simulator.github.io?tab=readme-ov-file): Assembler and emulator for the Intel 8085 microprocessor.

**Getting Started**

To get a local copy up and running, follow these steps.

**Prerequisites**

In order to run this project you need:

A working computer
Connection to internet
Setup

**How to Run**

To run the program, you need an 8085 emulator or assembler. You can use emulators like DOSBox or TASM (Turbo Assembler). Here's how to run the program using e8085.exe:

1. Download and install 8085 simulator from [here](https://github.com/8085simulator/8085simulator.github.io?tab=readme-ov-file).
2. Clone this repository to your local machine.
3. Open 8085 simulator and load the `labveb1.asm` file.
4. Assemble the code by pressing the Assemble button.
5. Run the program by pressing the Run button or by pressing F10.
