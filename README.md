// Rock_Paper_scissor
// Rock paper scissor game based on conditional statements!!!
import java.util.*;
public class sps {
public static void main(String[] args) {
Scanner sc=new Scanner(System.in);
System.out.println("\nLet'us play rock papper scissor with Compueter and see who wins\n");
Random  rand=new Random();
int r=rand.nextInt(3);
System.out.println("\t\tEnter a number");
System.out.println("\t\t---------------");
System.out.println("\t\t0 for Rock");
System.out.println("\t\t1 for Paper");
System.out.println("\t\t2 for Scissors\n");
int no=sc.nextInt();
if(no==0)
{
System.out.println("\tYOU HAVE CHOSSEN ROCK\n");
}
else if(no==1)
{
System.out.println("\tYOU HAVE CHOSSEN PAPER\n");
}
else if(no==2)
{
System.out.println("\tYOU HAVE CHOSSEN SCISSORS\n");
}
if(no==r)
{
System.out.println("\t\tIT'S A TIE\n");
}
else if(r==0 && no==1)
{
System.out.println("\t\tHURRAY!!! YOU WON THIS GAME\n");
}
else if(r==0 && no==2)
{
System.out.println("\t\t YOU LOST THE GAME\n");
}
else if(r==1 && no==0)
{
System.out.println("\t\t YOU LOST THE GAME\n");
}
else if(r==1 && no==2)
{
System.out.println("\t\tHURRAY!!! YOU WON THIS GAME\n");
}
else if(r==2 && no==0)
{
System.out.println("\t\tHURRAY!!! YOU WON THIS GAME\n");
}
else if(r==2 && no==1)
{
System.out.println("\t\t YOU LOST THE GAME\n");
}
else {
System.out.println("\t\tWRONG CHOICE ENTERED\n");
}
if(r==0)
{
System.out.println("\tBECAUSE THE COMPUTER HAS CHOSEN ROCK\n");
}
else if(r==1)
{
System.out.println("\tBECAUSE THE COMPUTER HAS CHOSEN PAPER\n");
}
else if(r==2)
{
System.out.println("\tBECAUSE THE COMPUTER HAS CHOSEN SCISSORS\n");
}
else
{
System.out.println("WRONG CHOICE ENTERED");
}
}
}
