# coding_journey
This is my coding journey in MCA.
*********Pattern Print**********












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
