---
title: "Projects"
draft: false
---

# List of Projects that I've Done over time:

## [Lunar Turing-GAN Super-Resolution Model](https://github.com/rv4102/ISRO)
### Objective: Create a high-resolution map of the Moon using a pipeline of Image Super-Resolution models
1. Proposed a novel GAN-based architecture with turing test based adversaries for ensuring accurate reconstruction of craters and hills.
2. Achieved a competitive SSIM of 0.794 while increasing image spatial resolution from 5m per pixel to 30 cm per pixel, a 16x magnification.
3. Created a pipeline capable of tiling and super-resolving an image using Lunar T-GAN, HAT, RealESRGAN and sharpening algorithms.
4. Developed a Lunar Atlas by correcting coordinates & stitching together individual image patches from the Chadrayaan-2 TMC payload.

## [QNet](https://github.com/rv4102/qnet)
### Objective: Develop an efficient and performant CNN model to be trained on small datasets
1. Built an encoder-decoder based network with depth-wise separable convolutional layers which outperforms a standard U-Net model.
2. Utilized a novel [Unified Focal Loss](https://arxiv.org/abs/2102.04525) function, which works well with class imbalanced datasets like the training dataset, LandCover.AI.
3. Developed TensorFlow scripts to create a dataloader for an efficient input pipeline and to perform inference on variable-sized images.

## [Hospital Management System](https://github.com/rv4102/HMS)
### Objective: To design a web application for a hospital management system
1. Developed a python flask based web application to connect a MySQL database to a bootstrap front-end coupled with jinja templates.
2. Implemented user session management using flask-login and provided access control through python decorator functions.
3. Modelled entities in a real-life hospital using a relational database and its schema with support for querying & storage of patient data.

## [KGP-miniRISC Processor](https://github.com/rv4102/CompOrg-Lab/tree/main/A6_KGP_miniRISC_Processor)
### Objective: Designed a modular and extensible single-cycle execution unit for 32-bit Instruction Set Architecture rooted in RISC principles.
2. Developed an encoding format for a total of 23 data transfer, data manipulation, program sequencing, and control instructions.
3. Engineered a Von Neumann Architecture for ALU, Data Path, and pure combinational Control Unit for the ISA, shaping its functionality.
4. Successfully dumped the bitstream onto a Nexys A7 FPGA board using Xilinx ISE and ran programs (written in assembly) such as sorting and linear search.

## [Linux Shell Development](https://github.com/rv4102/OS-Lab/tree/main/A2)
### Objective: To create a shell that will run as an application program on top of the Linux kernel
1. Effectively managed process groups and employed signal handlers to monitor child processes and ensure synchronized execution.
2. Designed a CPU usage heuristic to detect fork bomb based malware and utilized the flock syscall to ensure exclusive access to files.
3. Implemented advanced features including background execution, pipelining, wildcard handling, and command history navigation.

## [Message Oriented TCP](https://github.com/rv4102/Networks-Lab/tree/main/A5)
### Objective: To build a message oriented TCP Protocol using socket programming
1. Created a library for ‘MyTCP’ protocol, guaranteeing reliable, in-order delivery of messages up to 5000 bytes using standard TCP sockets.
2. Utilized POSIX threads and mutex locks/ conditional signals to ensure synchronised access to global buffers used for messages.
3. Ensured that all global data structures were cleared on closure of socket and performed tests using simple client/ server programs.

<!-- ## [Students' Auditorium Management System](https://github.com/rv4102/AudiBooking)
1. Implemented a website to facilitate booking and overall management of an Auditorium with support for users such as Administrator, Salesperson and Accounts Clerk.
2. Backend created using Python Flask with support for OTP based login management and frontend written in Bootstrap + Jinja templates. -->