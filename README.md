# Simple-Calculator-with-c-
Calculator which performs basic Arithmetic Operation
Code

using namespace std;
# include <iostream>
int main () {
	int choice, choice1;
	int Number1, Number2;
	double result;
	
	
	do {
		cout<<"\n Calculator"<<"\n";
		cout<<" 1. +"<<"\n";
		cout<<" 2. -"<<"\n";
		cout<<" 3. *"<<"\n";
		cout<<" 4. /"<<"\n";
		cout<<"\nEnter Choice ";
		cin>>choice;
	if ( choice !=5)
		{
			switch (choice)
			{
				case 1:
					cout<<"Enter Number 1: ";
					cin>>Number1;
					cout<<"Enter second Number: ";
					cin>>Number2;
					result=Number1+Number2;
					cout<<"The addition of 2 Numbers are "<<endl;
					cout<< result <<endl;
					break;
					
				case 2:
					cout<<"Enter Number 1: ";
					cin>>Number1;
					cout<<"Enter Number 2: ";
					cin>>Number2;
					result=Number1-Number2;
					cout<<"The Subtraction of 2 Numbers are "<<endl;
					cout<< result <<endl;
					break;
					
				case 3:
					cout<<"Enter Number 1: ";
					cin>>Number1;
					cout<<"Enter Number 2: ";
					cin>>Number2;
					result=Number1*Number2;
					cout<<"The Multiplication of 2 Numbers are "<<endl;
					cout<< result <<endl;
					break;
					
				case 4:
					cout<<"Enter Number 1: ";
					cin>>Number1;
					cout<<"Enter Number 2: ";
					cin>>Number2;
					result=Number1/Number2;
					cout<<"The division of 2 Numbers are "<<endl;
					cout<< result <<endl;
					break;
				default:
					cout<<"Wrong Input";
		    	}
				
		}
   }while(choice=0);
	    cout <<"Program by Moeez Iqbal:";
	    system ("pause");
return 0;	
}
