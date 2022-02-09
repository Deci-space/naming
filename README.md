# deci-naming

### background 
There are many advantages to using namespace, and we are trying to create a naming convention 
that focuses on readability that applies to all programming languages.

### naming convention
| Object               | Notation   |
|:---------------------|:-----------|
| variables            | snake_case |
| constructor          | snake_case |
| function             | snake_case |
| argument             | snake_case |
| claass               | Snake_case | 
| field                | snake_case |
| method               | snake_case |
| method argument      | _snake_case |
| instance             | Snake_case |

### examples
examples are written in c++
```cpp
const int some_const = 1;

int dd_some_nummber(int some_var) {
  return some_var + some_const; 
}
```

```cpp
class Some_class_name {
  int some_var;
  
  void set_var(int _some_var) {
    some_var = _some_var
  }
}

int main() {
  int var = 1;
  Some_class_name Some;
  Some.set_ver(var);
}
```
