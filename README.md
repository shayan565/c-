#include<stdio.h>
int main()
{
	int x1, x2, y1, y2;
	float slope;
 x1=5;
 x2=3;
 y1=4;
 y2=2;
 printf ("x1=5\n");
 printf ("x2=3\n");
printf ("y1=4\n");
printf ("y2=2\n");

 slope=(y2-y1)/(x2-x1);
 printf("the slope is %.3f\n", slope);
}


#include<stdio.h>
int main()
{
	int a,b,c,temp;
	printf ("enter a number : ");
	scanf ("%d", &a);
	printf ("enter a number : ");
	scanf ("%d", &b);
	printf ("enter a number : ");
	scanf ("%d", &c);
	temp=a;
	a=b;
	b=c;
	c=a;
	printf ("the swapped value of a is %d\n",a );
	printf ("the swapped value of b is %d\n",b);
	printf ("the swapped value of c is %d\n",c);
	
}
