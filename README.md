# xv6-first-priority-scheduling
First Priority Scheduling in xv6 OS – Case Study &amp; Implementation on macOS
📌 Overview

This project implements First Priority Scheduling in the xv6 operating system, modifying its default round-robin scheduling to prioritize processes based on assigned priority levels. The implementation is tested and demonstrated on macOS, with a detailed case study analyzing its effects on system performance.

🔥 Features
	•	🛠 Modified xv6 Scheduler – Implements a priority-based scheduling algorithm.
	•	💻 Runs on macOS – Tested on MacBook M1 with QEMU.
	•	📊 Performance Analysis – Compares default vs. priority scheduling.
	•	📖 Case Study & Documentation – Includes step-by-step implementation details.

 🚀 Installation & Setup

1. Clone the Repository
2. git clone https://github.com/your-username/xv6-priority-scheduling.git
cd xv6-priority-scheduling

3.Install MacPorts from https://www.macports.org/.

4.Open a terminal window where I downloaded the OS.
5.Install Qemu by writing sudo port install qemu.
6.sudo port install i386-elf-gcc gdb.
6.Replace the existing Makefile to a new one with code:https://github.com/ashr123/XV6-MacOS-Makefile.
7.In order to run, write in the terminal window make qemu clean.
