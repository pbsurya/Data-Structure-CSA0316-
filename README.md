# Data-Structure-CSA0316-
Sum of two matrices
~~~
#include<iostream>
using namespace std;
int main()
{
	int n=3,m=3,i,j,sum=0;
	int a[3][3]={{1,2,3},{1,2,3},{1,2,3}};
	if(m==n)
	for(i=0;i<n;i++)
	{
		for(j=0;j<m;j++)
		cout<<a[i][j];
		cout<<"\n";
	}
	for(i=0;i<n;i++)
	{
		for(j=0;j<m;j++)
		sum+=a[i][j];
	}
	cout<<"sum of matrix:"<<sum;
	return 0;
}
~~~
![Screenshot (7)](https://github.com/pbsurya/Data-Structure-CSA0316-/assets/148762368/feb826b5-82ed-47bf-9241-968156a7ee4b)

