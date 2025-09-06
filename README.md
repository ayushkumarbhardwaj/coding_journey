# coding_journey
This is my coding journey in MCA.
*********Pattern Print**********
Square Print 



#include<iostream>
int main()
{




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
