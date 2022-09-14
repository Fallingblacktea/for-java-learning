```java
public class hello {
    public static void main(String[] args) {
        java.util.Scanner input = new java.util.Scanner(System.in);
        double a = input.nextDouble();
        double b = input.nextDouble();
        double c = input.nextDouble();
        double d = Math.pow(b, 2) - (4 * a * c);
        double r1 = (Math.pow(d,0.5)-b)/(2*a) ;
        double r2 = -(Math.pow(d,0.5)-b)/(2*a) ;
        if (d>0)
        System.out.println("The equation has two roots" + r1+" "+r2);
        else if (d==0)
        System.out.println("The equation has one roots" + r1);
        else if (d<0)
        System.out.println("The equation has no real roots");
    }
}
```
