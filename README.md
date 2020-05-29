# Dasturchilarklubi
#include<iostream>
#include <iomanip>
using namespace std;
int main()
{
	long long i,j,n;
	cin>>n;
	cout<<"    ";
	for(j=1;j<=n;j++)
	cout<<setw(3)<<j<<" ";
	cout<<endl;
	for(j=1;j<=3*n;j++)
	cout<<"__";
	cout<<endl;
	for(i=1;i<=n;i++)
	{
		cout<<i<<" | ";
		for(j=1;j<=n;j++)
		{
			
			cout<<setw(3)<<i*j<<" ";
		}
		cout<<endl;
	}
}
