# 实验4-3

- task4_3.java
```java
package task4_3;
import java.util.Scanner;
public class Task4_3 {
public static void main(String[] args) {
// TODO Auto-generated method stub
int x,y,z;
Scanner reader =new Scanner(System.in);
System.out.println("请输入x：");
x= reader.nextInt();
System.out.println("请输入y：");
y= reader.nextInt();
System.out.println("请输入z：");
z= reader.nextInt();
reader.close();
Maths mathtool=new Maths();
System.out.println("x和y的最大值"+mathtool.max(x, y));
System.out.println("x和y和z的最大值"+mathtool.max(x, y, z));
}
}
```

- Maths.java
```java
package task4_3;
public class Maths {
int max(int a, int b) 
    {
        if(a>=b) 
        {
            return a;
        }else
        {
            return b;
        }
    }

int max(int c, int d,int e) 
{
int s=0;
s=c;
if(d>s)
s=d;
if(e>s)
s=e;
return s;
} 
}
```

# 实验4-4

- task4_4.java
```java
package task4_4;
public class Task4_4 {
public static void main(String[] args) {
// TODO Auto-generated method stub
        Rectangle myRect1,myRect2;
        myRect1=new Rectangle();
        myRect1.width=10;
        myRect2=new Rectangle(4,5);
        System.out.println(myRect1.getArea());
        System.out.println(myRect2.getArea());
}
}
```

- rectangle.java
```java
package task4_4;
public class Rectangle {
double width;
double height;
Rectangle()
{
width=1;
height=1;
}
Rectangle(double w,double h)
{
width=w;
height=h;
}
double getArea()
{
return width*height;
}
}
```

# 实验4-5
