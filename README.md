# cce0326

## 計算商數 
```C
int main ()
{	
	int a,b;
	scanf("%d%d",&a,&b);
	printf("%d\n",a/b);
	}
```
## 三數極大
```C
#include <stdio.h>
int main ()
{
 int a,b,c;
 scanf("%d%d%d",&a,&b,&c);
 if(a>b&&a>c) printf("%d\n",a);
 else if(b>a&&b>c) printf("%d\n",b);
 else if(c>a&&c>b) printf("%d\n",c);
 }
 ```
 ## N數之和
 ```C
 #include <stdio.h>
int main()
{
	int N,num,sum=0;
	scanf("%d",&N);
	for(int i=1;i<=N;i++){
		scanf("%d",&num);
		sum+=num;
		
		}
		printf("%d\n",sum);
		}
 ```
 ##  絕對值函數
 ```C
 #include <stdio.h>
int f(int a)
{
if(a>0)
return a;
else return a*(-1);
}
int main(void)
{
	int n;
	scanf("%d",&n);
	printf("[%d]",f(n));
	return 0;
}
```
## 反序數字
```C
#include <stdio.h>
int f(int n )
{
	int p;
	int m =0;
	
	while(n>0)
	{
		p=n%10;
		n=n/10;
		m= p+m*10;
	}
	return m;
	}
	int main ()
	{
	int n,m;
	scanf("%d",&n);
	printf("%d+%d=%d\n",n,f(m),n+f(m));
	}
  ```
