# Nested-Loop 


```cpp
#include <bits/stdc++.h>
```

* This line includes **all standard C++ libraries** (it's a GCC-specific header, not standard but commonly used in competitive programming for convenience).

```cpp
using namespace std;
```

* This allows us to use standard library names (like `cin`, `cout`, `endl`) without prefixing them with `std::`.

---

### Main Code Logic

```cpp
int main() {
    int n;
    cin >> n;
```

* The program starts by **reading an integer `n`** from input (user provides this).
* `n` represents both the number of **rows** and **columns** to print.

---

### Nested Loops

```cpp
for (int i = 1; i <= n; i++) {
    for (int j = 1; j <= n; j++) {
        cout << j << " ";
    }
    cout << endl;
}
```

* The outer loop (`i = 1 to n`) controls the **number of rows**.
* The inner loop (`j = 1 to n`) prints **numbers from 1 to n** in each row.
* `cout << j << " "` prints each number followed by a space.
* `cout << endl;` moves to the next line after each row.

---

### Example Output

If the input is:

```
4
```

The output will be:

```
1 2 3 4 
1 2 3 4 
1 2 3 4 
1 2 3 4 
```

### Summary

The program prints a square grid of numbers from 1 to `n`, repeated `n` times, forming an `n x n` matrix where each row is identical.


