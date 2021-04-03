#include <iostream>
using namespace std;

int main() {
	// your code goes here
	int T;	
	cin>>T;	
	while(T--)
	{
	     int K,N;
	     int count=0;
	     string s;
	     cin>>N>>K;
	     cin>>s;
	    int i;
	    for(i=0;i<N;i++)
	    {
	        if(s[i]=='*'){
	            count++;
	             if(count==K)
	            {
	                cout<<"YES";
	                break;
	            }
	        }   
	           // if(s[i]!='*')
	        else{
	            count=0;
	        }
	        
	    }
	    if(i==N)
	    {
	        cout<<"No";
	    }
	   cout<<endl; 
	}
	
	return 0;
}
