import java.util.Random;
import java.util.Scanner;
import java.util.random.*;;
public class numberGame {
    
        
    
    public static void main(String[] args) {
        System.out.println( "------------------*NUMBER GAME*--------------------");
        System.out.println("RULE AND REGULATION OF GAME");
        System.out.println("*)you have to pick the number in range 1-100");
        System.out.println("*) maximum chance upto 3 entry.");
        Scanner sc=new Scanner(System.in);
        Random random=new Random();
        int randomIntRange=random.nextInt(100);
        
        
        int x=randomIntRange;
        int size=4;
        int score=0;

        
        for(int i=1;i<size;i++){
            System.out.print("ENTER YOUR "+i+ "  NO:");
           int  number =sc.nextInt();
            if (number>x) {
                System.out.println("This is not correct number: HINT|| YOUR NO IS GREATER");
                
            }
            else if (number<x) {
                System.out.println("This is not correct number: HINT|| YOUR NO IS LEASER");
                
                
            }
            if (number==x) {
                
                
                
                
                System.out.println("This is  correct number: congratulation");
                score++;
                System.out.println("your score is:"+score);
                score++;
                break;
            }
             System.out.println();
             System.out.println("--------------------------------------------");

            
          }
          System.out.println("YOUR SCORE IS:"+ score);

        System.out.println("------Your All Round is Over----");
        System.out.println("The correc no is:" + randomIntRange);
        System.out.println("Thank You!!!!");
        System.out.println("To Play again type : 1");
        int n=sc.nextInt();

        Random s=new Random();
        int sIntRange=random.nextInt(100);
        int y=sIntRange;
      if (n==1){
            
        for(int i=1;i<size;i++){
            
            System.out.print("ENTER YOUR "+i+ "  NO:");
           int number2=sc.nextInt();
            if (number2>y) {
                System.out.println("This is not correct number: HINT|| YOUR NO IS GREATER");
                
            }
            else if (number2<y) {
                System.out.println("This is not correct number: HINT|| YOUR NO IS LEASER");
                
                
            }
            if (number2==y) {
                
                
            
                
                System.out.println("This is  correct number: congratulation");
                score++;
                
                break;
            }
            System.out.println();

            
            
        }
        System.out.println("Your all Chances are over");
        System.out.println("The correc no is:" + sIntRange);
        System.out.println(score);
        //else{
           // System.out.println("------------END OF GAME-------------");
        }
        else{
            System.out.println("--------See You Again------");
        }
    }
}
