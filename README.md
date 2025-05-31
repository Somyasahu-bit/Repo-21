# Repo-21
Print even number in given range
//Print even number in given range
import java.util.Scanner;
class even{
    public static void main(String[] args){

    int n;
    System.out.println("Enter no. of term");
    Scanner r=new Scanner(System.in);
    n=r.nextInt();
    
    for(int i=0; i<=n; i=i+2)
    {
        System.out.println(i);
    }
    }
}
