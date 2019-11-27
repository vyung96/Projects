# Projects
# Letter frequency
# Counting the number of letters that appear

#include <stdio.h>
#include <string.h>
#include <stdlib.h>

int main() {
  char alphabet[26] = {a,b,c,d,e,f,g,h,i,j,k,l,m,n,o,p,q,r,s,t,u,v,w,x,y,z};
  char c;
  int sum[26];
  int total;
  float freq;
  int i;
  char letter;

  while ((c = getchar() != EOF))
  {
    total++;
    if (c == 'a' || c == 'A')
    {
      sum[0] = sum[0] + 1;
    }
  }

for(i = 0 ; i < 26 ; i ++)
  freq = sum[i]/total;
  letter = alphabet[i];
  if (sum[i] != 0)
  {
    printf()
  }
  
  

}
