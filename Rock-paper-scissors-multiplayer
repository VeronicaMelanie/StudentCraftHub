// Project 1.cpp : This file contains the 'main' function. Program execution begins and ends there.
//

#include <iostream>
#include <string>

using namespace std;
// Multiplayer "Piatra hartie foarfeca

void alegereUser1(int user1) {

    int piatra = 1;
    int hartie = 2;
    int foarfeca = 3;

    if (user1 == piatra) {
        cout << "Piatra" << endl;
    }
    else if (user1 == hartie) {
        cout << "Hartie" << endl;
    }
    else if (user1 == foarfeca) {
        cout << "Foarfeca" << endl;
    }
    else {
        cout << "Alege alt numar!!! DE LA 1 LA 3!!!!" << endl;
    }
}

void alegereUser2(int user2) {

    int piatra = 1;
    int hartie = 2;
    int foarfeca = 3;

    if (user2 == piatra) {
        cout << "Piatra" << endl;
    }
    else if (user2 == hartie) {
        cout << "Hartie" << endl;
    }
    else if (user2 == foarfeca) {
        cout << "Foarfeca" << endl;
    }
    else {
        cout << "Alege alt numar!!! DE LA 1 LA 3!!!!" << endl;
    }
}

void castigator(int user1, int user2) {
    if (user1 == user2) {
        cout << "Remiza" << endl;
    }
    else if ((user1 == 1 && user2 == 3) || (user1 == 2 && user2 == 1) || (user1 == 3 && user2 == 2)) {
        cout << "User1 ai castigat, felicitari!!!" << endl;
    }
    else {
        cout << "User2 a castigat, felicitari!!!" << endl;
    }
}

int main()
{
    int user1;
    int user2;

    cout << "Bine ati venit la jocul de 'piatra, hartie, foarfeca'" << endl;
    cout << "Alegeti-va elementu:" << endl;
    cout << "1. Piatra." << endl;
    cout << "2. Hartie." << endl;
    cout << "3. Foarfeca." << endl;

    cout << "Pick a number from 1-3 :D User 1: ";
    cin >> user1;
    alegereUser1(user1);

    cout << "Pick a number from 1-3 :D User 2: ";
    cin >> user2;
    alegereUser2(user2);

    castigator(user1, user2);

    return 0;
}
