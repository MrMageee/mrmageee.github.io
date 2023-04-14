<https://github.com/MrMageee/mrmageee.github.io/raw/main/task4_4.rar>

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

- task4_5.java
```java
public class Task4_5 {
public static void main(String[] args) {
// TODO Auto-generated method stub
Rectangle myRect1,myRect2;
        myRect1=new Rectangle();
        myRect1.width=10;
        myRect2=new Rectangle(4,5);
        System.out.println(myRect1.getArea());
        System.out.println(myRect2.getArea());
        myRect1=myRect2;
        System.out.println(myRect1.getArea());
}
}
```

- rectangle.java
```java
package task4_5;
public class Rectangle {
double width;
double height;
double getArea()
{
return width*height;
}
Rectangle(double w,double h)
{
width=w;
height=h;
}
Rectangle()
{
width=1;
height=1;
}
}
```
