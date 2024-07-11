# Fast-primes-CH32V003-OLED-display
Finding all 32-bit primes starting at eg 3,000,000,001. The gap between the primes is about 22 at this magnitude. The CH32V003 8-pin RISC-V 32 bit processor runs at 24MHz and finds about 23 primes a second using a fast deterministic Miller–Rabin algorithm. An LED on PC4 is flashed for each prime found.
The display is a 128x32 OLED.

Demo at https://www.youtube.com/watch?v=rPzlua1Xw1I

Developed on PlatformIO using the CH32V003fun minimalist environment https://github.com/cnlohr/ch32v003fun

## Repository overview
The repositry contains C code, a font file and PlatformIO environment files.
