# change-cases-of-particular-string.cpp
//C program to change cases of particular string.
#include <stdio.h>

int main() {
    int i;
    char a[20]="AmitKumar"; 
    
    for(i=0;a[i];++i)
     if(a[i]>=65 && a[i]<=90)
      printf("%c",a[i]+32);
     else 
      printf("%c",a[i]-32);
    return 0;
}
