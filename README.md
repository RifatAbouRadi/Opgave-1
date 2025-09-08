

# Lunar Lander Control

This project implements a simple control logic for a lunar lander based on altitude, following the given flowchart.

## Project Description
The program decides whether the lander's thruster should be **on** or **off** depending on the altitude:

- If altitude > 100 → Thruster OFF  
- If 0 < altitude ≤ 100 → Thruster ON  
- If altitude ≤ 0 → Thruster OFF  

This logic ensures the lander slows down safely before reaching the surface.

## Files
- `src/main.c` → Contains the program code
- `.gitignore` 
- `README.md` → Documentation for the project

## How to Compile and Run
Using **clang** (or gcc):
clang main.c 
.\\a.exe
