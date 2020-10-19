#include<stdio.h>
int main(){

	double a,b,c;
printf("Input 3 numbers:");
scanf("%1f  %1f %1f", &a,&b,&c);

if(a>=b && a>=c)
printf("%.2f is the largest number",a);

if(b>=a && b>=c)
printf("%.2f is the largest number",b);

if(c>=a && c>=b)
printf("%.2f is the largest number",c);

	return 0;

}
