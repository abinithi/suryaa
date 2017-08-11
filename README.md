#include<stdio.h>
int main()
{
char c;
int is lower case vowel, is upper case vowel;
printf("enter an alphabet:");
scanf("%c,&c);
is lower case vowel =(c =='a'||c =='e'||c =='i'||c =='o'||c =='u');
is upper case vowel =(c =='A'||C =='E'||C =='I'||C =='O'||C =='U');
if(is lower case vowel || is upper case vowel)
printf("%c is a vowel.",c);
else
printf("%c is a consonant.",c);
return 0;
]
