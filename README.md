# class
#include<stdio.h>
#include<conio.h>
class point
{
int maths,science;
public:
point(intx,inty)
{
science=x;
maths=y;
}
void display()
{
cout<<"maths="<<maths;
cout<<"science="<<science;
}
};
void main()
{
point p1(22,33);
p1.display();
}
