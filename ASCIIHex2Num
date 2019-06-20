#include <stdio.h>

#define ASCIIHex2Num(__ASCII__) (__ASCII__ & 0x0F) + 9*((__ASCII__ & 0x40) >> 6)
#define Num2ASCII_CAP(__Num__) (__Num__ | 0x30) + 7*(__Num__ / 10 )

int main ()
{
  int i;
  char c;
  i = ASCIIHex2Num ('e'); //convert e to 14
  i = ASCIIHex2Num ('E'); //convert e to 14
  printf("%i", i);
  c = Num2ASCII_CAP (i); //convert 14 to E
  printf ("%c", c);

  return 0;
}


