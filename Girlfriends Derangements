import java.util.*;
public class Main {
    public static int Girlfriends_Derangements(int n){
        if(n==1) return 0;
        if(n==2) return 1;
        return (n - 1) * (Girlfriends_Derangements(n - 1) + Girlfriends_Derangements(n - 2));
    }
    public static void main(String args[]) {
        // Your Code Here
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        System.out.print(Girlfriends_Derangements(n));
    }
}

//https://hack.codingblocks.com/app/contests/3774/3420/problem
