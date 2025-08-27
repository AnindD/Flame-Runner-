# Flame Runner 
By: Anindit Dewan & Andrew Lee 

Last Updated: May 2025 

## Summary 📖
Introducing Flame Runner, a game where users must move their character across a complex maze whilst dodging fireballs from various directions. 

Every time a user moves onto the next level a unique maze is created using a pathfinding algorithm. The game incorporates smooth game physics of fireballs so that they are bouncing back appropriatley.  To finish it off, the game incorporates both sound & animation when moving between various screens. 

The game was implemented in C and executed on a RISC-V soft-core processor reconfigured on a DE1-SoC FPGA board 

## Skills and Technologies Used 🖥️
* Coded using embedded C and assembly 
* Use of external I/O peripherals: VGA, Audio Speaker & PS/2 Controller 
* Use of interrupts to control timer and screen transition using assembly 
* Game physics and movement control
* RISC-V 

## Video Demonstration 🎥

## Block Diagram 👷

## User Installation ⚙️
If you would just like to simulate the game on your home PC, simply open the simulation software, [![CPULator](https://cpulator.01xz.net/?sys=rv32-de1soc)] and open the C file provided within this project. 

You can also compile and flash it using a DE1-oOC directly given you have the software installed. 

## Things to Improve  🔨
* Better visuals instead of pure squares for fireballs and user character. 
