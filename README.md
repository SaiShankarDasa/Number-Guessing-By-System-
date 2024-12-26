# Number-Guessing-By-System-
You have to think about a number in your mind from 0to60and based on your inputs the system will guess the number
#include<stdio.h>
void main()
{
    int x,y,z,a,b,c;
    int sum=0;
    printf("First Card:\n");
    printf("1 3 5 7 9\n");
    printf("11 13 15 17 19\n");
    printf("21 23 25 27 29\n");
    printf("31 33 35 37 39\n");
    printf("41 43 45 47 49\n");
    printf("51 53 55 57 59\n");
    printf("Is that number present in this list? if yes then enter 1 or else enter 0\n");
    scanf("%d",&a);
    if (a==1)
    sum=sum+1;
    printf("Second Card:\n");
    printf("2 3 6 7 10\n");
    printf("11 14 15 18 19\n");
    printf("22 23 26 27 30\n");
    printf("31 34 35 38 39\n");
    printf("42 43 46 47 50\n");
    printf("51 54 55 58 59\n");
printf("Is that number present in this list? if yes then enter 1 or else enter 0\n");
    scanf("%d",&b);
    if (b==1)
    sum=sum+2;
    printf("Third Card:\n");
    printf("4 5 6 7 12\n");
    printf("13 14 15 20 21\n");
    printf("22 23 28 29 30\n");
    printf("31 36 37 38 39\n");
    printf("44 45 46 47 52\n");
    printf("53 54 55 60\n");
printf("Is that number present in this list? if yes then enter 1 or else enter 0\n");
    scanf("%d",&c);
    if (c==1)
    sum=sum+4;
    printf("Fourth Card:\n");
printf("8 9 10 11 12\n");
    printf("13 14 15 24 25\n");
    printf("26 27 28 29 30\n");
    printf("31 40 41 42 43\n");
    printf("44 45 46 47 56\n");
    printf("57 58 59 60\n");
printf("Is that number present in this list? if yes then enter 1 or else enter 0\n");
    scanf("%d",&x);
    if (x==1)
    sum=sum+8;
    printf("Fifth Card:\n");
printf("16 17 18 19 20\n");
    printf("21 22 23 24 25\n");
    printf("26 27 28 29 30\n");
    printf("31 48 49 50 51\n");
    printf("52 53 54 55 56\n");
    printf("57 58 59 60\n");
printf("Is that number present in this list? if yes then enter 1 or else enter 0\n");
    scanf("%d",&y);
    if (y==1)
    sum=sum+16;
    printf("Sixth Card:\n");
printf("32 33 34 35 36\n");
    printf("37 38 39 40 41\n");
    printf("42 43 44 45 46\n");
    printf("47 48 49 50 51\n");
    printf("52 53 54 55 56\n");
    printf("57 58 59 60\n");
printf("Is that number present in this list? if yes then enter 1 or else enter 0\n");
    scanf("%d",&b);
    if (b==1)
    sum=sum+32;
    printf("Your Guessed Number is %d",sum);
}
