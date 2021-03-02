# linear-search
//linear search in c++
//TC is O(n)


#include<iostream>
using namespace std;
int main()
{
    int element,i;
   // cout<<"enter size of the array";
    int size;
    cin>>size;
    int arr[size];
    //cout<<"enter the elements in array";
    for(int i=0;i<size;i++)
    {
        cin>>arr[i];
    }
  //  cout<<"enter the element that is to be searched";
    cin>>element;
    for(int i=0;i<size;i++)
    {
        if(element==arr[i])
        {
            cout<<"element is found at position "<<i+1;
            break;
        }}
        if(i==size)
        {
            cout<<"element is not present in the array";
        }
    
    //return 0;
}
/*


#include <iostream>
using namespace std;
int main()
{
  int list[100],size,i,search_el;//Initializing variables.

  cout<<"Enter size of the list: ";//Taking inputs.
  cin>>size;

  cout<<"Enter elements of the list: ";
  for(i = 0; i < size; i++)
  cin>>list[i];

  cout<<"Enter the element to be search: ";
  cin>>search_el;
  
  //Searching element using linear search.
  for(i = 0; i < size; i++)
  {
     if(search_el == list[i])
     {
        cout<<"Element is found at "<< i+1 <<" place in the list";
        break;
     }
  }
  if(i == size)
     cout<<"Element is not present in the list";
  
}
*/
