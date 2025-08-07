# 🧪 InputValidate

A lightweight and practical C++ library for validating user input — including integers, strings, ranges, and formatted dates — in a safe and structured way.

---

## 🔗 Dependencies

This library depends on the following custom utilities:

- [`clsDate`](https://github.com/w0mmd/Date-Lib-cpp) – for date handling  
- [`clsString`](https://github.com/w0mmd/String-Lib-cpp) – for string processing

📌 **Ensure both libraries are included in your project** before using `InputValidate`.

---

## 🔧 Features

- ✅ Validate integer and float inputs  
- ✅ Enforce input within specific numeric ranges  
- ✅ Clean and validate string input  
- ✅ Handle and validate date components using `clsDate`  
- ✅ Lightweight, beginner-friendly  
- ✅ Built with standard C++ and clsDate/clsString only

---

## 📁 Project Structure

```
InputValidate/
├── include/
│   └── InputValidate.h
└── README.md
```

---

## 📌 Usage Example

```cpp
#include "clsString.h"
#include "clsDate.h"
#include "InputValidate.h"

int main() {
    int age = clsInputValidate::ReadIntNumber("Enter your age: ");
    float salary = clsInputValidate::ReadFloatNumber("Enter your salary: ");
    std::string name = clsInputValidate::ReadString("Enter your name: ");
    short day = clsInputValidate::ReadDay("Enter your birth day: ");
    return 0;
}
```

---

## 👤 Author

Created by **Mohammad Alhamad**  
This library was developed as a helper module to simplify and secure user input in C++ applications.
