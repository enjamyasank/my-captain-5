# my-captain-5
#include<studio.h>
void main()
{int i,j,a[i][j],sum=0;
 for(i=0;i<=3;i++)
{for(j=0;j<=3;j++)
scanf("%d",&a[i][j]);
}
for(i=0;i<=3;i++)
{for(j=0;j<=3;j++)
if(i==j)
sum=sum+a[i][j];
}
printf("sum of diagonal elements is %d",sum);
}
