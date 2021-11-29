# -Haywood--cop3330-ch-3--ex-8-
Chapter 3, Exercise 8

/*
 *  UCF COP3330 Fall 2021 Assignment 5 Solution
 *  Copyright 2021 Kaylah Haywood
 */


import java.util.Scanner;

public class IntegerEvenOdd
{
  public static void main(String args[])
  {
    int num;
    System.out.println("Enter an Integer number:");
    
    //User input of integer value//
    Scanner input = new Scanner(System.in);
    num = input.nextInt();

    // Even number if integer number is divisible by 2, else odd number//
    if ( num % 2 == 0 )
        System.out.println("The value entered is even");
     else
        System.out.println("The value entered is odd");
  }
}
