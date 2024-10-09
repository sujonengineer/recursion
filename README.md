# recursion
#include<stdio.h>
#include<math.h>

int factorial(int);
int main(){

int a  = 5;
int f = factorial(a);

printf("a : %d\n", a);
printf(" Factorial of a: %d\n", f);

}
int factorial(int x){
	int i;
	int f = 1;
	for(i = 5; i >= 1; i--){
		f *= i ;
	}

	return f;
}
