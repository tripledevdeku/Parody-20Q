#include <string> // this will add strings
#include <iostream> // 'i' equals in, 'o' equals out, and stream means the flow of information between them
// this is a comment, it will not effect the code
using namespace std;

int main() // 'int' means integer
{
	int points = 0;
	char choice;
//only nine questions because program will get confused if there is  a 1 and a 0

	cout << "                                               Welcome to 9 Questions!" << endl;
	cout << "                                           -= A parody of 20 Questions =-" << endl;
	cout << "                                                 Press 0 to start!" << endl;
	cin >> choice;

	if (choice == '0')
	{
		// if you hit '0' then it will start.
		cout << "Hint: I'm thinking of an animal." << endl;
	}
	cout << "                                        .-=*^{                        }^*=-." << endl; // -
	cout << "                                         ||              [Q1]            || " << endl; //  |
	cout << "                                         ||  Is it big?     Is it small? || " << endl; //  |- This is just a bunch of over ascii-arted menus
	cout << "                                         ||   Press 1         Press A    || " << endl; //  |
	cout << "                                        -==================================-" << endl; // -
	cin >> choice;

	if (choice == '1')
	{
		cout << "                                             Yes, it's fairly large." << endl;
		points++;
	}
	if (choice == 'A' || choice == 'a')
	{
		cout << "                                                      No." << endl;
	}
	cout << "                                        .-=*^{                        }^*=-." << endl;
	cout << "                                          ||             [Q2]            || " << endl;
	cout << "                                          || Is it cute?    Is it ugly?  || " << endl;
	cout << "                                          ||   Press 2       Press B     || " << endl;
	cout << "                                        -==================================-" << endl;
	cin >> choice;

	if (choice == '2')
	{
		cout << "                                                      Yes, very." << endl;
		points++; // this adds points for the end. the more correct questions you ask, the more points you get
	}
	if (choice == 'B' || choice == 'b')
	{
		cout << "                                                          No." << endl;
	}
	cout << "                            .-=*^{                                                         }^*=-." << endl;
	cout << "                             ||                              [Q3]                             || " << endl;
	cout << "                             || Does is live in the Jungle?    Does it live in the Mountains? || " << endl;
	cout << "                             ||            Press 3                           Press C          || " << endl;
	cout << "                            -===================================================================-" << endl;
	cin >> choice;
	if (choice == '3')
	{
		cout << "                                               No it would get too hot." << endl;
	}
	if (choice == 'C' || choice == 'c')
	{                                         // it lives in a plain-mountain biome i.e. south dakota, where it climbs on rocky's family
		cout << "                                                    Yes, it does." << endl;
		points++;
	}
	cout << "                               .-=*^{                                                }^*=-." << endl;
	cout << "                                ||                          [Q4]                        || " << endl;
	cout << "                                ||   Can you see it's skin?    Does it have rough skin? || " << endl;
	cout << "                                ||      Press 4                      Press D            || " << endl;
	cout << "                               -==========================================================-" << endl;
	cin >> choice;

	if (choice == '4')
	{
		cout << "                                             No, unless you shear it." << endl;
		points++;
	}
	if (choice == 'D' || choice == 'd')
	{
		cout << "                                                  No, not really." << endl;
	}
	cout << "                                      .-=*^{                                      }^*=-." << endl;
	cout << "                                        ||                      [Q5]                 || " << endl;
	cout << "                                        ||    Does it eat meat?    Is it vegetarian? || " << endl;
	cout << "                                        ||        Press 5               Press E      || " << endl;
	cout << "                                      -================================================-" << endl;
	cin >> choice;

	if (choice == '5')
	{
		cout << "                                         No, it chews cud like a cow or deer." << endl;
	}
	if (choice == 'E' || choice == 'e') // this means you can either put 'E' or 'e' and it wouldn't matter, the code would still progress
	{
		cout << "                                                          Yes." << endl;
		points++;
	}
	cout << "                                      .-=*^{                                          }^*=-." << endl;
	cout << "                                       ||                      [Q6]                      || " << endl;
	cout << "                                       || Is it edible? If so is it good?   Is it smart? || " << endl;
	cout << "                                       ||           Press 6                   Press F    || " << endl;
	cout << "                                      -====================================================-" << endl;
	cin >> choice;
	// you chose a bad question, so the program will promptly kick you out
	if (choice == '6')
	{
		cout << "                           You monster! Who would want to eat an such a cute animal?! Get out of my sight!" << endl;
		cout << "                                                        Press Z to exit." << endl;
		cin >> choice;
	}
	if (choice == 'Z' || choice == 'z')
	{
		exit(0);
	}
	if (choice == 'F' || choice == 'f')
	{
		cout << "                                   Yes, it can communicate with others using body positions." << endl;
		points++;
	}
	cout << "                                    .-=*^{                                                 }^*=-." << endl;
	cout << "                                     ||                        [Q7]                          ||  " << endl;
	cout << "                                     ||   Is it a cow?   Is it used for it's hair/fur/fiber? ||  " << endl;
	cout << "                                     ||       Press 7                   Press G              ||  " << endl;
	cout << "                                    -===========================================================-" << endl;
	cin >> choice;

	if (choice == '7')
	{
		cout << "                                                   Nice try, but no." << endl;
	}
	if (choice == 'G' || choice == 'g')
	{
		cout << "                                                           Yep!" << endl;
		points++;
	}
	cout << "                                    .-=*^{                                                 }^*=-.  " << endl;
	cout << "                                     ||                           [Q8]                        ||   " << endl;
	cout << "                                     ||     Is it a well known animal?   Is it a rare animal? ||   " << endl;
	cout << "                                     ||             Press 8                    Press H        ||   " << endl;
	cout << "                                    -===========================================================-  " << endl;
	cin >> choice;

	if (choice == '8')
	{
		cout << "                                         Yes, it's often admired for it's cuteness." << endl;
		points++;
	}
	if (choice == 'H' || choice == 'h')
	{
		cout << "                                                     No, it's quite common." << endl;
	}
	//THE FINAL COUNTDOWN 
	cout << "                                       .-=*^{                                           }^*=-." << endl;
	cout << "                                        ||              IT'S THE FINAL ROUND!             || " << endl;
	cout << "                                        ||      Is it a sheep?        Is it an alpaca?    || " << endl;
	cout << "                                        ||         Press 9                Press I         || " << endl;
	cout << "                                       -=====================================================-" << endl;
	cin >> choice;

	if (choice == '9')
	{
		cout << "                                        Nope. It's an alpaca! Better luck next time." << endl;
		cout << "                                     You finished the game with " << points << " points." << endl;
		cout << "                                                     Press Y to exit." << endl;
	}
	if (choice == 'I' || choice == 'i')
	{
		points++;
		cout << "                                                     Congrats! You won!" << endl;
		cout << "                                        You finished the game with " << points << " points!" << endl;
		cout << "                                                    Thanks for playing!" << endl;
		cout << "                                                      Press Y to exit." << endl;
	}
	if (choice == 'Y' || choice == 'y')
	{
		exit(0);
	}
   
}
