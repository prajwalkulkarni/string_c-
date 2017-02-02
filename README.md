# string_c++

#include<iostream>
#include<string>

using namespace std;
int main()
{
int i,j,k;
string words[10],temp;
cout << "No of strings ? " <<endl;
cin >> k;

for(i=0;i<k;++i)
{
cout << "Enter string " << i+1;
getline(cin,words[i]);
cout << endl;
}

for(i=0;i<k;++i)
{
for(j=i+1;j<i;++j)
{
if(a[i] > a[j])
{
temp = a[i];
a[i] = a[j];
a[j] = temp;
}

cout << "strings in sorted order" <<endl;

for(i=0;i<k;++i)
cout << words[i] <<endl;

return 0;
}
