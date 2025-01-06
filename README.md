# Game Development Journey in C++

Welcome to my game development journey! I'm learning game development using **C++**, and this repository will contain my projects, code snippets, and experiments.

## About Me

```cpp
#include <iostream>
#include <string>

class AboutMe {
public:
    // Personal Information
    std::string name = "Selim";
    std::string location = "Turkey";
    std::string language = "C++, English";
    std::string goal = "Learning game development with C++";
    std::string currentFocus = "Building basic games and experimenting with game engines like Unreal Engine";

    // Displaying the information
    void displayInfo() {
        std::cout << "Hello, I'm " << name << "!" << std::endl;
        std::cout << "Location: " << location << std::endl;
        std::cout << "Languages: " << language << std::endl;
        std::cout << "Goal: " << goal << std::endl;
        std::cout << "Currently Focused On: " << currentFocus << std::endl;
    }
};

int main() {
    AboutMe me;
    me.displayInfo();
    return 0;
}
