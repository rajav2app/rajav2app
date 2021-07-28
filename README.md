/*  Linear Search */
class LinearSearch
{
static int search(int arr[],int x)
{
for(int i=0;i<=arr.length();i++)
{
if(x==arr[i]
return i;
else
return -1;
}
}

public static void main(String args[])
{
int[] arr={12.13,14,45,67};
int x=45;
int result=search(arr,x);
if(result==-1)
System.out.println("Search Item Not found");
else
System.out.println("Index of search Element is "+result);
}
}
