# Hey, whats up?
**My names Salvatore**
*Im a 4/5 Computer Engineer*

> Here is a List of my hobbies
> and interests
- Drawing
- Robotics
- Playing Video Games
- Sports

## Top 3 Favorite Foods
1. pasteles
2. Sushi
3. Hot Dogs

### Here is some Fibonacci sequence code
`#include <iostream>
using namespace std;
void fib(int input)
{
    int x = 1;
    int hold = 1;
    int output = 1;
    for(int i = 0; i<input-1; i++) //Creates a loop based of what you set fib to minus 1
    {
        if(i==0)    //sets the first two sequences of fibbonaci to 1 and 1 without using math
        cout<< 1 << ", ";
        else if(i==1)
        cout<< 1 << ", ";
        else
        {
            output = x+hold; 
            cout<< output << ", "; //prints out the value of fib(i)
            x=hold; //x becomes the next value in the sequence
            hold=output; //hold becomes the previous answer from the last equation
        }
    }
    output = x+hold;
    cout<< output;
}
int main()
{
    int smile;
    cout<<"Please choose a number \n";
    cin >> smile; //User inputs a number 
    fib(smile); //The user input is taken and the fibbonacci sequence is run to that value
}`

---


