#include "pch.h"
#include <stdio.h>
#include <iostream>
#include <string>

using namespace std;

struct automobile
{
	string mark;
	string manufacturer;
	string type;
	int year;
	string date;
};

int main()
{
	setlocale(LC_ALL, "RU");
	automobile autom;

	autom.mark = "Toyota";
	autom.manufacturer = "China";
	autom.type = "passenger car";
	autom.year = 2001;
	autom.date = "27.06";
	if (autom.mark == "Toyota" &&  autom.year < 2007) {
		cout << "марка машины " << autom.mark << endl;
		cout << "производитель " << autom.manufacturer << endl;
		cout << "тип " << autom.type << endl;
		cout << "год" << autom.year << endl;
		cout << "дата" << autom.date << endl;
	}
	else {
		cout << "nothing";
	}
	}
