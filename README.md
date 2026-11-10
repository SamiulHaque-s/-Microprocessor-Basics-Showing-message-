# Showing Messages on the Screen and Making a New Line (8086 Assembly)

This is a simple assembly language program from my Microprocessor Lab.

## What the program does

It prints three lines on the screen:

Fast Name : M M Samiul
Last Name : Haque
Blood Group : B +

## What I learned

- How to store text in the data segment using `db`
- How to set up the data segment with `MOV AX, @DATA` and `MOV DS, AX`
- How to print a string using `AH = 9` and `INT 21H` (the string must end with `$`)
- How to make a new line by printing `0DH` (carriage return) and `0AH` (line feed) with `AH = 2`
- How to end the program using `AH = 4CH`

## Files

- `one.asm` : the assembly source code
- `Microprocessor_Lab_Report.docx` : my full lab report with screenshots

## Tools used

- VS Code (code editor)
- TASM (Turbo Assembler)
