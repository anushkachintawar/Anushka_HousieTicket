# Housie Ticket Generator in MATLAB
## Overview
This MATLAB script generates random Housie tickets with 15 numbers each, organized in a 3x9 grid. Each row contains 5 randomly selected numbers from the specified range (1-90).
## Rules to generate a ticket
1. Each row should have 5 elements.
2. Column range:
     Cloumn 1: 1-10
     Column 2: 11-20
     ...
     Column 9: 81-90
3. Unique number in each column (in ascending order) with no column empty.
## About the program
Create a 3x9 binary matrix with 5 '1' in each row and each column contains atleast one '1'.
Create another 3x9 matrix according to above column range using randperm command.
Multiply the two matrices.
Sort the non-zero elements column-wise and replace all '0' with ' '.
Resultant matrix is a housie ticket.
## Output
![image](https://github.com/anushkachintawar/Anushka_HousieTicket/assets/116649480/e0afe99d-c0b1-4a23-ab0c-e6c1f9a0735d)
