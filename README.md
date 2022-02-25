# Printing-fibbonacci-series
/*11. A Fibonacci sequence is defined as follows: the first and second terms in the sequence are 0 and 1. 
Subsequent terms are found by adding the preceding two terms in the sequence.
 Write a C program to generate the first n terms of the sequence. 
*/
#include<stdio.h>
int main()
{   int i;
	printf("0");
	printf("\n1");
	int a = 0;
	int b = 1;
	for(i=2;i<10;i++){
		
		int term = a+b;
	    printf("\n%d",term); 
	    a=b;
	    b=term;
		
	}	
     
		
	}
