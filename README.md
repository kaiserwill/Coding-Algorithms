Coding-Algorithms
=================

//Check if an  int is a palindrome
#include<stdio.h>
using namespace std;


bool is Palindrome(int num){
  n = num; //create a dummy variable that holds original value of num
  reverse = 0; 
  while(num>0){
    digit = num%10;
    reverse = reverse*10+digit
    num /=10;
  return n==reverse;
}
