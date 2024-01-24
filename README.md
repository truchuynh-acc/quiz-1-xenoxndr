[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/tYncE4AO)
# quiz1_class_and_objects

## Instructions:
Please fill in the blank
```cplus
/*
* Alejandro Espinoza:
*/

// Question: Create a C++ class representing a car with attributes like model, year, and color. Include a method to display car details.
// Answer: --------------------------------------- here

#include <iostream>
#include <string>
using namespace std;
class Car {
private:
    string model;
    int year;
    string color;
public:
    //Setter methods
    void setModel(){ //model setter
        cout << "What is the model of your car: ";
        cin >> model;
    }
    
    void setYear(){ //year setter
        cout << "What is the year of your car: ";
        cin >> year;
    } 
    void setColor(){
        cout << "What is the color of your car: ";
        cin >> color;
    }

    //Getter methods
    void getModel(){ //model getter
        cout << "Your car model is: " << model;
    }

    void getYear(){ //year getter
        cout << "The year of your car is: " << year;
    }

    void getColor(){
        cout << "You car is " << color << "!";
    }

    void displayDetails() {
        
        cout << "Model: " << model << ", Year: " << year << ", Color: " << color << std::endl;
    }
};

int main() {
    Car myCar;
    
    //Set all variables using setter methods
    myCar.setColor();
    myCar.setYear();
    myCar.setModel();
    
    myCar.displayDetails();

    return 0;
}

```
