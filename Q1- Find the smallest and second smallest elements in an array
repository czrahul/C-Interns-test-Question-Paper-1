#include<iostream>
using namespace std;

void small(int a[], int n)
{
	int s = a[0], ss=a[0];
	for(int i = 1; i < n; i++)
	{
		if(a[i] < s)
		{
			if(ss > s)
			{
				ss = s;
			}
			s = a[i];
		}
	}
	
	cout<<"The smallest element is "<<s;
	cout<<" and the second smallest element is "<<ss;
}
int main()
{
	int n;
	cin>>n;
	int arr[n];
	for(int i = 0; i<n; i++)
	{
		cin>>arr[i];
	}
	small(arr, n);
	return 0;
}
