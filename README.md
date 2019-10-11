# Hacktoberfest 2019
Edit to your hearts content.

This repository is dedicated to [G-Dawg](https://github.com/heygillianm).

Help? Trying to figure out how to create a class called "Win Percentage" with these specifications:
- User enters total number of games played
- User enters total number of games won
- Calculates and prints percentage of games won
- Must validate the input so it's not an error
- will continue to prompt user until valid input is given

All while using while loop statements. 

This is all I have so far:

import java.util.Scanner;
import java.util.DecimalFormat;

public class WinPercentage
{
  public static void main (String [] args) {
    Scanner scan = new Scanner(System.in);

    System.out.println("Enter number of games played:");
    int played = scan.nextInt();
    System.out.println("Enter number of games won:");
    int won = scan.nextInt();

    while ()

    double percentage = won/played;
    
  }
}
