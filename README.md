# a3_10669995
#include <iostream>
using namespace std;
int main(){
	int marks;
	
	cout<<"enter marks"<<endl;
	cin>>marks;
	if(marks<=100 && marks>=80)
	{cout<<"Grade A:"<<endl;
	}
	else if(marks<=79 && marks>=75)
	{cout<<"Grade B+:"<<endl;
	}
	else if(marks<=74 && marks>=70)
	{cout<<"Grade B:"<<endl;	
	}
	else if(marks<=69 && marks>=65)
	{cout<<"Grade C+:"<<endl;
	}
	else if(marks<=64 && marks>=60)
	{cout<<"Grade C:"<<endl;
	}
	else if(marks<=59 && marks>=55)
	{cout<<"Grade D+:"<<endl;
	}
	else if(marks<=54 && marks>=50)
	{cout<<"Grade D:"<<endl;
	}
	else if(marks<=49 && marks>=45)
	{cout<<"Grade E:"<<endl;
	}
	else if(marks <=44 && marks>=0)
	{cout<<"Grade F:"<<endl;
	}
	else
	{cout<<"INVALID:"<<endl;
	}
	return 0;
}
