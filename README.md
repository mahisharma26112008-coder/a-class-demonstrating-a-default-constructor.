# a-class-demonstrating-a-default-constructor.

#include<iostream>
using namespace std;
class student {
    int roll_number;
    int marks;

    public:

    student(){
        roll_number=1001;
        marks=500;
    }

    void display(){
        cout<<"roll number"<<roll_number<<"\n";
        cout<<"marks"<<marks<<"\n";
    }
};
int main(){
    student s1;

  s1.display();

    return 0;
}
