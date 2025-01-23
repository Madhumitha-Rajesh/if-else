# if-else

CODING-

package pkgif.pkgelse;
import java.util.Scanner;

public class IfElse {

    public static void main(String[] args) {
        // TODO code application logic here
        Scanner sc=new Scanner(System.in);
        int num;
        System.out.print("enter the number:");
        num=sc.nextInt();
        if(num%2==0){
            System.out.println("it is an even number");
        }
        else{
            System.out.println("it is an odd number");
        }
    }
    
}

Output-

enter the number:43
it is an odd number
