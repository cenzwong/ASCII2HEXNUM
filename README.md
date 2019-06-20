# ASCII2HEXNUM
Simple define to calculate the ASCII 2 HEXNUM, and HEXNUM 2 ASCII

Copy this:

#define ASCIIHex2Num(__ASCII__) (__ASCII__ & 0x0F) + 9*((__ASCII__ & 0x40) >> 6)

#define Num2ASCII_CAP(__Num__) (__Num__ | 0x30) + 7*(__Num__ / 10 )
