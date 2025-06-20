

## C++ Basic Program 

### 📌 **1. `#include<iostream>` – Input/Output Ka Darwaza**

* Ye line compiler se bolti hai:

  > "Bhai! Mujhe screen pe print karne aur user se input lene ke tools chahiye."
* `iostream` = **input-output stream**
* Bina iske, `cin` aur `cout` kaam nahi karenge!

---

### 📌 **2. `using namespace std;` – Shortcut for Standard Tools**

* C++ ke har tool ka original naam `std::cout`, `std::cin` hota hai.
* Har baar `std::` likhna boring hai?
  ➤ Toh hum bolte hain:

  > "Bhai, standard tools ko shortcut se bulaunga."

**Without it:**

```cpp
std::cout << "Hello";
```

**With it:**

```cpp
cout << "Hello";
```

---

### 📌 **3. `int main()` – Yahin Se Shuru Hoti Hai Kahaani**

* Ye hai **program ka entry gate**.
* Jab program run hota hai, **sabse pehle yahi chalti hai**.
* `int` ka matlab: Ye function **return karega ek number**, usually `0`.

> Socho jaise ek movie ka “main character” – poori story yahin se start hoti hai!

---

### 📌 **4. `{ }` – Kaam Ka Ghar**

* Ye **curly braces** bolte hain:

  > "Jo bhi kaam karna hai, iske andar hi likhna."

* `main()` function ka sara kaam `{ ... }` ke andar hota hai.

---

### 📌 **5. `return 0;` – Mission Successful!**

* Ye line bolti hai:

  > "Sab kuch sahi chala, koi error nahi. Program khatam ho gaya happily!"

* Agar kuch gadbad hoti toh hum `return 1;` de sakte the.

---

### ✅ **FULL FEEL KE SAATH EXAMPLE:**

```cpp
#include<iostream>          // Input/output tools
using namespace std;        // Use standard tools without std::

int main() {                // Entry point
    cout << "Hello, World!"; // Output to screen
    return 0;               // Tell system: All good!
}
```

---

## 💡 Ek Line Mein:

> **C++ ka program ek formal letter jaisa hota hai:**
> 🔹 *Pehle batate ho kin tools ki zarurat hai,*
> 🔹 *Phir bolte ho kin logon (namespace std) se baat karni hai,*
> 🔹 *Phir apni main baat likhte ho (main function),*
> 🔹 *Aur end mein politely bolte ho — sab sahi hua, return 0!*

---
