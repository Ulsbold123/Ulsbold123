#include <stdio.h>
#include <string.h>
int main (){
  char a[20] , b[20],
c[20] ; 
int i , len ;
  scanf ("%s" , a );
  len = strlen (a);
  for (i=0 ; i<len ; i++)
    b[i] = a[i] +3;
  printf("decrypt : %s\n" , b );
    return 0 ;
}
