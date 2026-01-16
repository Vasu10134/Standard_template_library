to use Vector  
#include<vector>  
#include<bits/stdcpp.h>  
  
Syntax of Vector  
vector<int> vec;  
  
to put elements onto vector, use  
vec.push_back(10);  
  
Iterating a vector  
for(int i=0;i<vec.size();i++)  
{  
  cout<<vec[i]<<" ";  
}  
  
Range Based Iteration  
for(int x : vec)  
{  
  cout<<x<<" ";  
}  
  

to pop element from vector, use
vec.pop_back();
