# Print-sum-of-n-numbers-using-Recursion
import javax.lang.model.SourceVersion;

//Print sum of n naturals numbers
public class Recursion {
  public static void Sum(int i,int n,int sum)
  {
    if(i==n)
    {
      sum=sum+i;
      System.out.println(sum);
      return;
    }
    sum=sum+i;
    Sum(i+1,n,sum);
    //System.out.println(i);
  }
 public static void main(String[] args)
 {

  Sum(1,5,0);
 }
    
}
