#include<iostream>
#include<vector>
#include<algorithm>

using namespace std;

int main()
{
	vector<int> v;
	int s;
	do
	{
		if(v.empty())
		{
			cin>>s;
			v.push_back(s);
			cout<<"median- "<<v[0]<<"\n";
		}
		else
		{
			v.push_back(s);
			int n = v.size();
			int j = n-2;
			
			while(j >= 0 && v[j]>s)
			{
				v[j+1] = v[j];
				j--;
				
			}
			v[j+1] = s;
			
			if(n%2 == 0)
			{
				cout<<"median- "<<(v[n/2]+v[n/2-1])/2<<"\n";
			}
			else
			{
				cout<<"median- "<<v[n/2]<<"\n";
			}
		}
		cin>>s;
	}
	while(s != NULL);
	
}
