# largestnumber
import java.util.*;
class greastest
{
    public static void main(String args[])throws Exception
    {
        Scanner sc= new Scanner(System.in);
        int a,b,c;
        System.out.println("enter 3 number");
        a=sc.nextInt();
        b=sc.nextInt();
        c=sc.nextInt();
        if((a>b)&&(a>c))
        {
            System.out.println(+a+"is greastest number");
        }
        else if(b>c)
        {
            System.out.println(+b+"is greastest number");
        }
        else
        {
            System.out.println(+c+"is greastest number");
        }
    }
}
          
         
