/*
* C Program to Add two numbers using pointers
*/
#include <stdio.h>
#include <conio.h>
 
int main(){
     
    int firstNumber, secondNumber, sum;
    /* Pointers declaration */
    int *firstNumberPointer, *secondNumberPointer;
    printf("Enter two numbers \n");
    scanf("%d %d", &firstNumber, &secondNumber);
    /* Pointer assignment*/
    firstNumberPointer = &firstNumber;
    secondNumberPointer = &secondNumber;
     
    sum = *firstNumberPointer + *secondNumberPointer;
    printf("SUM = %d", sum);
    getch();
    return 0;
}
