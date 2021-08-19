#include <iostream>
using namespace std;

int main() {
	// your code goes here
	string s;
	cin>>s;
	int z = 0;
	int o = 0;
// 	int yes = 1;
// 	if(s[0]=='z') z++;
// 	else if(s[0]=='o') o++;
	for(int i=0;i<s.size();i++)
	{
	   // if(s[i-1]=='o'&&s[i]=='z'){
	   //     yes = 0;break;
	   // }
	    if(s[i]=='z')   z++;
	    else if(s[i]=='o') o++;
	}
	if(2*z==o) cout<<"Yes";
	else
	    cout<<"No";
// 	else
// 	    cout<<"No";
	return 0;
}
