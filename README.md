//# cpp
//some basic code for beginners
#include<iostream>
using namespace std;
int main()
{
	int i,j,k;
	cin>>i>>j>>k;
	if(i>j&&i>k)
	{
		cout<<i<<" is maximum "<<endl;
	}
	else if(j>i&&j>k)
	{
		cout<<j<<" is maximum"<<endl;
	}
	else
	{
		cout<<k<<" is maximum"<<endl;
	}
	return 0;
}
