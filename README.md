# part3-Practical_5
package calc;
public class div {
public float div(int diva,int divb)
{
return diva/divb;
}
}
//--------------------------//
package calc;
public class mul {
public int mul(int mulp,int mulq)
{
return mulp*mulq;
}
}
//--------------------------//
package calc;
public class sub {
public int sub(int subx,int suby)
{
return subx-suby;
}
}
//--------------------------//
package calc;
public class sum {
public int sum(int suma,int sumb)
{
return suma+sumb;
}
}
//--------------------------//
import calc.*;

public class main {

    public static void main(String[] args) {
        sum obj1 = new sum();
        System.out.println("sum =" + obj1.sum(20, 10));
        sub obj2 = new sub();
        System.out.println("sub =" + obj2.sub(20, 10));
        mul obj3 = new mul();
        System.out.println("mul =" + obj3.mul(20, 10));
        div obj4 = new div();
        System.out.println("div =" + obj4.div(20, 10));
        System.out.println("Created by Manav luhar  ID NO. 21CE063");

    }

}
