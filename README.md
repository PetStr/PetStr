## I'm PetStr 

This is a brief abstract of my experience regarding writing advanced and compiled software.

I do have experience with working with Matlab, Octave, Simulink, C, C++, to some extent Python and some other obscure languages.

Generally I prefer to write for a multitude of platforms. I usually change ruthlessly between Linux, Windows and MacOS. If theoretically possible most software projects are written for many platform user whatever compilers that are available. I want to know how things works so I would like to stay close to the metal so to say. I feel that if I am close, if something stops working it is easier to figure out what went wrong. Hiding behind a fancy IDE does not help there. I prefer to understand how the build systems work and the dependencies that is used. Feel that is dangerous just to trust cmake to find dependencies without understanding that they mean.

* Editors, right now mainly using Visual Studio Code, I used Emacs and vim in the past.
* Build systems, I prefer Makefile. looking into cmake.  
* Language, C++, is there anything else?
* Compilers, anything out there. gcc, clang. compliant and multi platform.
* GUI - GTKMM. enuff said.
* Software platform, anything out there. Linux-intel, Linux-arm, Win10-intel, MacOS.
* Hardware platforms, x86_32, x86_64, ARM-v7, ARM-M1.

Example of the types of software I have written:
* Scientific calculations. Calculation of gas data thermodynamic stuff. Gas equilibrium, adiabatic flame temperature, general gas data. A sample of this code is just about to be released. 
* Real time control (well sort if, soft real time control). Combustion engine lab control. During my postgraduate studies I wrote an engine control / rig control program that was used for experiments on a combustion engine. In short we used cylinder pressure signal to control combustion. Using Simulink Controller in the loop. Together with expert from automatic control department several advanced control topologies were tested. PID, LQG, MPC[pdh thesis].
* Data acquisition. AD sampling.
* Database query (SQL) mostly MSSQL.
* Software for analysis (C++), (ODBC), ([GTKMM](https://gtkmm.gnome.org/en/index.html)) into spreadsheet.
* Controlling and monitoring sensors and actuators through Controller Area Network. Kvaser CAN and socketcan.
* Handling (UDS) ISO 14229 and ISO-TP CAN, analysis and pentesting. 
* Processing log data. blf and customs formats.
* [lblf](https://github.com/PetStr/lblf) is a small tool for parsing BLF.  

I have never really worked with embedded stuff. Mostly it has been PC based. 

Coding style. I prefer to start with a concrete example. Start to get something working and then evolved gradually go for appropriate abstractions. 

<!--
- 👋 Hi, I’m @PetStr
- 👀 I’m interested in life
- 🌱 I’m currently learning life
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
-->
