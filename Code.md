# Code Notation
**MAIN RULE:** No AI! All your code must be humanmade and only humanmade. You have to understand your algorithms and can to describe your choice. If you didn't know how to realize algorithm, you can use google or ask AI (but only to understand the principle, and not to get the code). All your code must be sent for review by teamlead, and you must be rewrite all code if you cant describe that works. Teamlead check -
- Indev-code notation conformity
- Performance of algorithms
- Documentation

## Naming
| Object | Naming Format | Example |
| :--- | :--- | :--- |
| Class | CamelCase | `TestClass` |
| Functions & Methods | snake_case | int_get_value |
| System Functions & Methods | _snake_case | _get_value |
| Args | Short but clear | input_value |
| Variables | name | counter | 
| System Variables | _name | _counter | 
| Constants | UPPER_CASE | MODULE_VERSION |

## Code style
| Parameter | Description |
| :--- | :--- |
| Line Length | Length of line must be less or equals to 100. Only for readable and simple understand |
| Comments | Comments must be short and clean, length must be less or equals to 50 |
| Documentation | All algorithms must be described on comments (or only has name), and magic numbers and values must be documented too. Your docs must be exhaustive and clean, in one style |
| Dependency Managment | Try to avoid dependencies and write only with std lib, but if you use libs or frameworks you must add then name to `REQUIREMENTS` file |

## OOP 
Principles -
- **SOLID**: You have to know a solid principles to write clean architecture.
- **System Design**: Before writing think about architecture of code and imagine how to realize that.

## Project structure
All projects has same structure like -
```
./
  src/
    PROJECT_NAME/
      lib/
      main_file
      README.md
  README.md
  ... (system files and other)
```
