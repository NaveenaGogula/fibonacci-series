# fibonacci-series
import java.util.*;

public class Main {
    public static void main(String[] args) {
      Scanner sc=new Scanner(System.in);
      int n=sc.nextInt();
      int n1=0,n2=1,n3;
      if(n>0){
        System.out.print(n1+" "+n2);
        for(int i=2;i<n;i++){
          if(n==1){
           System.out.println(n1);
         }
          if(n==2){
            System.out.print(n1+" "+n2);
          }
          else{
            n3=n1+n2;
            System.out.print(" "+n3);
            n1=n2;
            n2=n3;
          }
        }
      }
      else{
        System.out.println("please enter valid seqence");
      }
  }
}
