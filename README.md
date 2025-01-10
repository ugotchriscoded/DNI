# Proyect - DNI

## :bulb: Project description
<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

I created a console application that calculates the letter of the **DNI** *(National Identity Document)*.

### Algorythm
- The number must be **between 0 and 99999999**
- We take the complete number of up to **8 digits** of our ID, divide it by **23** and keep the remainder of said division **(modulo 23)**
- Depending on the result, **from 0 to 22**, it will correspond to one of the following letters: *T, R, W, A, G, M, Y, F, P, D, X, B, N, J, Z, S, Q, V, H, L, C, K, E* (these data must be in a **database table**)
- If the data entered is NOT a number, a **message** must be indicated that *"the data entered is incorrect"* and the user must be asked again.
- The process **must be repeated** until the user enters a **valid number**.
- Everything will be done by **json** *(Api)*.

## Requirements

## :eye_speech_bubble: Project overview

## Project Diagram (BBDD)

## :scroll: Installation requirements

## :scroll: Installation

## Documentation (Endpoints)

## :white_check_mark: Tests

### Coverage

## Authors

## Languages

## Tools
