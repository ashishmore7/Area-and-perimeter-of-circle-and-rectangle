#include<stdio.h>
void main ()
{
	int d,r,choice,a,p,l,w,choice1;
	printf ("What your looking for : Enter 1 for Circle and Enter 2 for Rectangle : ");
	scanf("%d",&d);
if (d==1)
	{
		printf ("Enter the radious : ");
		scanf("%d",&r);
		printf ("Enter 1 for Area of circle : Enter 2 for Circumference of circle : ");
		scanf ("%d",&choice);
		if(choice==1)
		{
		a=3.14*(r*r);
		printf("Area of circle is : %d",a);
		}
		if(choice==2)
		{
		p=2*3.14*r;
		printf("Circumference of circle is : %d",p);
		}
	}
if (d==2)
	{	
		printf ("Enter the length : ");
		scanf("%d",&l);
		printf ("Enter the Width : ");
		scanf("%d",&w);
		printf ("Enter 1 for Area of Rectangle : Enter 2 for Perimeter of Rectangle : ");
		scanf ("%d",&choice1);
		if(choice1==1)
		{
		a=l*w;
		printf("Area of rectangle is : %d",a);
		}
		if(choice1==2)
		{
		p=2*(l+w);
		printf("Perimeter of rectangle is : %d",p);
		}
	}
}
