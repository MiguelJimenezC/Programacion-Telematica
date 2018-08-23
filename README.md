# Programacion-Telematica
#include <iostream>


using namespace std;
int main(int argc, char** argv) {
	
	float sueldo;
    cout<<"Ingresa tu sueldo actual ";
    cin>>sueldo;
    
    if(sueldo>=0 && sueldo<=1000)
    {
    	sueldo=sueldo+(sueldo*.18);
    	cout<<sueldo;
	}
	else if(sueldo>=1001 && sueldo<=1100)
	{
		sueldo=sueldo+(sueldo*.15);
    	cout<<sueldo;
	}
	else if(sueldo>=1101 && sueldo<=1200)
	{
		sueldo=sueldo+(sueldo*.12);
    	cout<<sueldo;
		
	}else if(sueldo>=1201 && sueldo<=1300)
	{
		sueldo=sueldo+(sueldo*.10);
    	cout<<sueldo;
	}else if(sueldo<1300)
	{
		sueldo=sueldo+(sueldo*.8);
    	cout<<sueldo;
	}
	return 0;
}
