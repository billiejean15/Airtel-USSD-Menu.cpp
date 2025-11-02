#include <iostream>
using namespace std;

int main() {
    int choice;

    cout << "Welcome to Airtel *117# Menu" << endl;
    cout << "1. Buy Data Bundle" << endl;
    cout << "2. Check Balance" << endl;
    cout << "3. Airtime Recharge" << endl;
    cout << "4. Make Payment" << endl;
    cout << "5. Exit" << endl;

    cout << "\nEnter your choice: ";
    cin >> choice;

    // For now, just echo the choice
    cout << "You selected option: " << choice << endl;

    return 0;
    switch(choice) {
    case 1:
        cout << "\n--- Buy Data Bundle ---" << endl;
        cout << "1. Daily Bundles" << endl;
        cout << "2. Weekly Bundles" << endl;
        cout << "3. Monthly Bundles" << endl;
        break;

    case 2:
        cout << "\n--- Your Balance ---" << endl;
        cout << "Main Balance: ZMW 50.00" << endl; // Just simulating
        break;

    case 3:
        cout << "\n--- Airtime Recharge ---" << endl;
        cout << "Enter Recharge PIN: (Simulation only)" << endl;
        break;

    case 4:
        cout << "\n--- Make Payment ---" << endl;
        cout << "1. Pay Bills" << endl;
        cout << "2. Send Money" << endl;
        break;

    case 5:
        cout << "Thank you for using Airtel *117#." << endl;
        break;

    default:
        cout << "Invalid choice. Try again." << endl;
        int subChoice;

cout << "\n--- Buy Data Bundle ---" << endl;
cout << "1. Daily Bundles" << endl;
cout << "2. Weekly Bundles" << endl;
cout << "3. Monthly Bundles" << endl;
cout << "Enter your choice: ";
cin >> subChoice;

switch(subChoice) {
    case 1:
        cout << "You selected Daily Bundles (Simulation)." << endl;
        break;
    case 2:
        cout << "You selected Weekly Bundles (Simulation)." << endl;
        break;
    case 3:
        cout << "You selected Monthly Bundles (Simulation)." << endl;
        break;
    default:
        cout << "Invalid bundle choice." << endl;
        cout << "\nEnter amount to pay: ";
double amount;
cin >> amount;

cout << "Processing payment of ZMW " << amount << "..." << endl;
cout << "Payment successful! (Simulation)" << endl;
while(true) {
    // display menu here
    // handle choices
    if(choice == 5) break; // exit when user selects Exit
}

}
}
}

