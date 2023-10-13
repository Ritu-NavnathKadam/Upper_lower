# Upper_lower
#include<stdio.h>
void main()
{
int n;
printf("enter a character:-");
scanf("%c",&n);


printf("ASCII value of %c is %d",n,n);

if(n<58 && n>48)
printf(" \nIt is digit");
else 
printf("\n It is character");

if(n<122 &&n>97)
printf("\nin lowercase");
else
printf("\nin uppercase");


}






