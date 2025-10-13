
class Solution {
  public:
    bool checkYear(int n) {
        // code here
        if((n%400==0) || (n%4==0 && n%100!=0))
        {
            return true;
        }
        else {
            return false;
        }
    }
};









class Solution {
  public:
    /*Function to count even and odd elements in the array
     * arr : Array with its elements
     */
    pair<int, int> countOddEven(vector<int> &arr) {
        // your code here
        int a=0;
        int b=0;
        int n= arr.size();
        for(int i=0;i<n;i++)
        {
            if(arr[i]%2==0)
            {
                a++;
            }else{
                b++;
            }
            
            
        }
        return {b,a};
    }
};









class Solution {
  public:
    bool isEven(int n) {
        // code here
        if(n%2==0)
        {
            return true;
        }
        return false;
    }
};






// User function template for C++
class Solution {
  public:
    // Function to return sum of elements
    int arraySum(vector<int>& arr) {
        // code here
        int sum=0;
        int n=arr.size();
        for(int i=0;i<n;i++)
        {
            sum=sum+arr[i];
        }
        return sum;
    }
};




// Sum of n natural number cube 
// User function template for C++

class Solution {
  public:
    int sumOfSeries(int n) {
        // code here
        return ((n*(n+1)/2)*(n*(n+1)/2));
    }
};






// User function Template for C++
class Solution {
  public:
    int sumOfSquares(int n) {
        // code here
        double a = (n*(n+1)*(2*n+1))/6;
         return a;
        
    }
};




Simple Interest

// User function Template for C++

class Solution {
  public:
    double simpleInterest(int P, int R, int T) {
        // code here
        double a=(P*R*T)/100.0;
        return a;
    }
};


# coding_journey
This is my coding journey in MCA.
*********Pattern Print**********





    A 
    B B
    C C C
    D D D D
    E E E E E
    int i;
    for(i=0;i<5;i++)
    {
        for(int j=0;j<=i;j++)
        { char a='A'+i;
            cout<<a<<" ";
        }cout<<endl;
    }



    A B C D E 
    A B C D
    A B C
    A B
    A
    int i;
    for(i=5;i>=1;i--)
    {
        for(char j='A';j<'A'+i;j++)
       {
         cout<<j<<" ";
       }cout<<endl;
    }



    A 
    A B
    A B C
    A B C D
    A B C D E
    int i;
    for(i=1;i<=5;i++)
    {
        for(char j= 'A';j<'A'+i;j++)
        {
            cout<<j<<" ";
        }cout<<endl;
    }





1 
0 1
1 0 1
0 1 0 1
1 0 1 0 1
int i,j,start;
for(i=1;i<=5;i++)
{
    if(i%2==0)
    start=0;else start=1;
    for(j=1;j<=i;j++)
    {
        cout<<start<<" ";
        start=1-start;
    }cout<<endl;
}










1      1
12    21
123  321
12344321
int i,j;
for(i=1;i<=4;i++)
{
    for(j=1;j<=i;j++)
    {
        cout<<j;
    }
    for(j=1;j<=2*(4-i);j++)
    {
        cout<<" ";
    }
    for(j=i;j>=1;j--)
    {
        cout<<j;
    }cout<<endl;
}








Square Print 

#include<iostream>
int main()
{

1 
2 3 
4 5 6 
7 8 9 10 
11 12 13 14 15 


int i,j,a=1;
for(i=1;i<=5;i++)
{
    for(j=1;j<=i;j++)
    {
        cout<<a<<" ";
        a++;
    }cout<<endl;
}







    

*
**
***
****
*****
****
***
**
*
   int i,j;
   for(i=0;i<5;i++)
   {
    for(j=0;j<=i;j++)
    {
      cout<<"*";
    }
    for(j=0;j<5-i-1;j++)
    {
        cout<<" ";
    }cout<<endl;
   }
   for(i=0;i<4;i++)
   {
    for(j=0;j<4-i;j++)
    {
      cout<<"*";
    }
    for(j=0;j<=i;j++)
    {
        cout<<" ";
    }cout<<endl;
   }













     *
    ***
   *****
  *******
 *********
 *********
  *******
   *****
    ***
     *
int i,j;
for(i=0;i<5;i++)
{
    for(j=0;j<5-i;j++)
    {
        cout<<" ";
    }
    for(j=0;j<2*i+1;j++)
    {
        cout<<"*";
    }
    for(j=0;j<5-i;j++)
    {
        cout<<" ";
    }cout<<endl;
}
for(i=0;i<5;i++)
{
    for(j=0;j<i+1;j++)
    {
        cout<<" ";
    }
    for(j=0;j<2*(5-i)-1;j++)
    {
        cout<<"*";
    }
    for(j=0;j<i+1;j++)
    {
        cout<<" ";
    }cout<<endl;
}






 *********
  *******
   *****
    ***
     *
for(i=0;i<5;i++)
{
    for(j=0;j<i+1;j++)
    {
        cout<<" ";
    }
    for(j=0;j<2*(5-i)-1;j++)
    {
        cout<<"*";
    }
    for(j=0;j<i+1;j++)
    {
        cout<<" ";
    }cout<<endl;
}







     *
    ***
   *****
  *******
 *********
int i,j;
for(i=0;i<5;i++)
{
    for(j=0;j<5-i;j++)
    {
        cout<<" ";
    }
    for(j=0;j<2*i+1;j++)
    {
        cout<<"*";
    }
    for(j=0;j<5-i;j++)
    {
        cout<<" ";
    }cout<<endl;
}


    12345
    1234
    123
    12
    1
    int i,j;
    for(i=5;i>=1;i--)
    {
        for(j=1;j<=i;j++)
        {
            cout<<j;
        }cout<<endl;
    }








    *****
    ****
    ***
    **
    * 
  int i,j;
  for(i=1;i<=5;i++)
  {
    for(j=5;j>=i;j--)
    {
        cout<<"*";
    }cout<<endl;
  }










    1
    22
    333
    4444
    55555
int i,j;
for(i=1;i<=5;i++)
{
    for(j=1;j<=i;j++)
    {
        cout<<i;
    }cout<<endl;
}









     1 
     12
     123
     1234
     12345
  int i,j;
  for(i=1;i<=5;i++)
  {
    for(j=1;j<=i;j++)
    {
        cout<<j;
    }cout<<endl;
  }






      * 
      *  *
      *  *  *
      *  *  *  *
      *  *  *  *  *
 int i,j;
 for(i=1;i<=5;i++)
 {
    for(j=1;j<=i;j++)
    {
        cout<<" * ";
    }cout<<endl;
 }












.........>PATTERN PRIINT<.........


     *  *  *  *  * 
     *  *  *  *  * 
     *  *  *  *  * 
     *  *  *  *  * 
     *  *  *  *  * 
    int i,j;
    for(i=1;i<=5;i++)
    {
        for(j=1;j<=5;j++)
        {
           cout<<" * ";
        }cout<<endl;
    }
    return 0;
}
#include<iostream>
int main()
{ int a,b,max;
cout<<"Enter a Number :";
cin>>a>>b;
max=max(a,b);
cout<<"Maximum Number is:"<<max;
return 0;
}
