## RSA Implementation using BRAM on Xilinx ISE and Spartan-6 FPGA
This project is an implementation of the RSA (Rivest-Shamir-Adleman) encryption algorithm using Block RAM (BRAM) on the Xilinx ISE design suite and targeting the Spartan-6 FPGA. The primary objective of this implementation is to reduce the hardware resource utilization by utilizing BRAM for storing the values of the modulus operation.
## Table Of Contents
 - [Introduction](#introduction)
 - [Project Overview](#Project-Overview)
 - [Requirements](#Requirements)
 - [Usage](#Usage)
 - [Acknowledgments](#Acknowledgments)
## introduction
RSA is a widely-used public-key encryption algorithm that enables secure communication between parties over an insecure network. This implementation focuses on optimizing the hardware utilization by utilizing BRAM for storing intermediate values during the modulus operation, reducing the overall complexity of the design.
## Project Overview
This project is developed using Xilinx ISE, a popular design suite for FPGA development. It targets the Spartan-6 FPGA board for the implementation of the RSA encryption algorithm. The utilization of BRAM allows for efficient storage and retrieval of intermediate modulus values, resulting in reduced hardware requirements.
## Requirements
To run this project, you need the following:

 - Xilinx ISE Design Suite (compatible with Spartan-6 FPGA)
 - Spartan-6 FPGA board
 - Computer with necessary drivers and software for FPGA development
## Usage
To use this project, follow these steps:
 1- Open the Xilinx ISE Design Suite and create a new project.
 2- Add the project files to the project directory.
 3- Modify the necessary parameters in the project files according to your requirements (e.g., key size, data inputs, clock frequency).
 4- Configure the project settings, such as the target device (Spartan-6 FPGA) and constraints.
 5- Run the synthesis and implementation process in Xilinx ISE to generate the programming file (.bit).
 6- Load the generated programming file onto the Spartan-6 FPGA using the appropriate programming tools.
 7- Connect the required input/output devices to the FPGA board.
 8- Power on the FPGA board and observe the output of the RSA encryption algorithm.
## Acknowledgments
This project was developed as part of [Mohamed Ayman]'s [NajahNow FPGA Course]. I would like to acknowledge the guidance and support provided by [Abdelrahman elshebinny].
