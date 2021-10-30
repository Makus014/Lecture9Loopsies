# Lecture9Loopsies


//bruteforceaatack I
  #include <iostream>
  #include <string>
  #using namespace
  
	int main() {
	
	string pw = "246";
	string input;

	cout << "Enter Password! " << endl;
	cin >> input;
	
	while (input != pw) {
		system("Cls");
		cout << "Enter Password!" << endl;
		cin >> input;
	}
	cout << "Welcome to Secured Company" << endl;

  return 0;
  }
  
  
  //Bruteforceattack II
  #include <iostrean>
  #include <string>
  using namespace std;
  
  int main() {

	string spassword = "246";
	string epass;
	int lock = 5;
	cout << "Enter Password!" << endl;
	cin >> epass;

	while (spassword != epass && lock > 0) {

		cout << "You have entered incorrect password, try again\n";
		cin >> epass;
		lock--;
	}
	while (spassword == epass) {
		cout << "you have entered the correct password!" << endl;
		break;
	}
  }
  
  
  
  //Improvement
  #include <iostream>
using namespace std;

  int main()
  {

	char Input;

	do {
		cout << "Would you like to quit (Y/N)?" << endl;
		cin >> Input;


		while (Input == 'n' || Input == 'N') {
			cout << "Okay get back to work!" << endl;
			return 0;
		}
	}

	while ((Input != 'Y') && (Input != 'y')); {
	cout << "Okay, pack your things! Goodbye!" << endl;
	return 0;
	} 
  
  
  //Loopy loopsies
  #include <iostream>
using namespace std;



  int main() {
	int myInt;
	int counter=0;

	cout << "Lets count 1 to five!" << endl;
	cin >> myInt;

	while (counter < myInt) {
		cout << counter + 1 << endl;
		counter++;
	}

	return 0;
  }

                               
                               
                               
  
