# -p4c.c
 Find the Largest of Three Numbers
#include <stdio.h>

int main() {
     int a,b,c,largest ;
  printf ("enter three numbers: ");
  scanf("%d %d %d",&a,b,c);
  if(a>=b && a>=c){
     largest =a;
  }else if (b>=a && b>=c){
     largest= b ;
  }else{
     largest =c;
}
printf("the largest number is :%d\n",largest );
return 0;
