# include<iostream>
# include<string>
using namespace std;
int main()
{
	string name;
	
	float Bath;
	float Dollar=30.63;
	float Euro =0.0287;
	cout << "input Bath is:";
	cin >> Bath;
	cout <<   " ****Exchange Rate**** "  << endl;
	cout << Bath << " Bath is:"<< Bath/Dollar<<"Dollar"<<endl;
	cout << Bath << " Bath is:" << Bath*Euro << "Euro" << endl;
	
	
	return(0);
}

