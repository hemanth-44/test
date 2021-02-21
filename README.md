#include<stdio.h>
#include<conio.h>
#include<string.h>
Void main()
{
Char s[5];
Int I, J, len,Del=0;
Printf("enter n of strings");
Scanf("%s",&n); 
For(i=0;i<n;i++)
{
Printf("%s",&s); 
}
For(i=0;i<n;i++)
{

For(j=0;j<len;j++)

{
If(s[j]!=s[j-1])
{
Printf("%c",s[j]);

}
Else
{
Printf("%c",s[j-1]);
Del++
}
If(s[j]==65||s[j]==66)
Printf("%c",&s[j]);
}
Printf("no of delations:%d",Del); 
}
