# Sharp PC-1211 BASIC Simulator

A browser-based simulator of the Sharp PC-1211 (TRS-80 PC-1) pocket computer's BASIC interpreter.

The Sharp PC-1211 (1980) was the world's first pocket computer with a BASIC interpreter. Its SC43177/SC43178 CPUs were never publicly documented, so this simulator implements the BASIC interpreter directly rather than emulating the CPU.

## Features

- 24-character LCD display with authentic green-on-dark rendering
- Full BASIC interpreter with 26 numeric and 26 string variables
- 1,800 bytes of program memory
- All four modes: RUN, PRO, RESERVE, DEF
- On-screen keyboard matching the physical PC-1211 layout
- Physical keyboard support
- Mode indicators: SHIFT, DEF, PRO, RUN, RESERVE, DEG/RAD/GRAD

## BASIC Commands

**Statements:** PRINT, INPUT, LET, IF/THEN, GOTO, GOSUB, RETURN, FOR/TO/STEP, NEXT, RUN, LIST, NEW, MEM, STOP, END, PAUSE, BEEP, REM, USING, DEGREE, RADIAN, GRAD

**Functions:** SIN, COS, TAN, ASN, ACS, ATN, LN, LOG, EXP, ABS, SGN, INT, DEG, DMS, SQR, RND, PI

## Quick Start

Open `index.html` in any modern browser. Type `PRINT 2+2` and press Enter.

## Credits

Inspired by [PockEmul](https://github.com/pockemul/PockEmul) by Remy Givert.

## License

MIT License - see [LICENSE](LICENSE) for details.
