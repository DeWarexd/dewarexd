```cpp
// https://github.com/DeWarexd/
using namespace std;

class Developer {
public:
    string name;
    vector<string> languages;
    vector<string> frontend;
    vector<string> backend;
    vector<string> tools;

    struct Contact {
        string discord;
        string email;
    } contact;

    Developer() {
        name = "DeWare";
        languages = {"C++", "C#", "Python", "TypeScript", "JavaScript", "Java", "Node.js"};
        frontend = {"Vue.js", "HTML5", "CSS3"};
        backend = {"Express.js", "MongoDB", "MySQL"};
        tools = {"Linux", "Android", "Electron", "Unity"};
        contact = {"dewarexd", "deware@proton.me"};
    }
};
```
