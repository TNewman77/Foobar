# Foobar
Divisable by 3, 5 or 15

import java.util.Scanner;

public class Foobar {

    public static void main(String[] args) {
        // TODO Auto-generated method stub
        System.out.println("Enter a number:");
        Scanner input = new Scanner(System.in);
        int x;
        x = input.nextInt();
         if (x % 3==0){
             System.out.println("foo");
             }then{
             if(x % 5==0){
             System.out.println("bar");
             }then{
             if(x % 15==0){
             System.out.println("foobar");
         }else{
             System.out.println("Please enter another number");
             
         }
    }

}
}
