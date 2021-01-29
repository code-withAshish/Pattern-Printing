# Can you C++ode these Triangle patterns with C++


### Pattern 1

input : 5
```
*
* *
* * *
* * * *
* * * * *
```

<details> <summary>Show Solution</summary>

Solution by : [@your_name](github_account_url)

```C++
#include <iostream>
using namespace std;
int main()
{
    int i, j;
    for (i = 0; i < 5; i++)
    {
        for (j = 0; j <= i; j++)
        {
            cout << " * ";
        }
        cout << "\n";
    }
}
```
</details>

---

### Pattern 2

input : 5
```
        *
      * *
    * * *
  * * * *
* * * * *

```

<details> <summary>Show Solution</summary>  

Solution by : [@your_name](github_account_url)

```C++
#include <iostream>
using namespace std;
int main()
{
    int i = 0, j = 0;

    for (i = 1; i <= 5; i++)
    {
        // Print spaces
        for (j = i; j < 5; j++)
        {
            cout << "  ";
        }
        // Print star
        for (j = 1; j <= i; j++)
        {
            cout << "* ";
        }
        // Print new line
        cout << "\n";
    }
}
```
</details>

---

### Pattern 3

input : 5
```
* * * * *
* * * *
* * *
* *
*
```

<details> <summary>Show Solution</summary>  

Solution by : [@your_name](github_accccount_url)

```C++
#include <iostream>
using namespace std;
int main()
{
    int i = 0, j = 0;

    for (i = 1; i <= 5; i++)
    {
        for (j = i; j <= 5; j++)
        {
            cout << " *";
        }

        // Print new line
        cout << "\n";
    }
}
```
</details>

---

### Pattern 4

input : 5
```
        *
      * * *
    * * * * *
  * * * * * * *
* * * * * * * * *
```

<details> <summary>Show Solution</summary>  

Solution by : [@your_name](github_account_url)

```C++

#include <iostream>
using namespace std;

int main()
{
    int n = 5;

    // loop for line number of lines
    for (int i = 1; i <= n; i++)
    {
        // loop to print leading spaces in each line
        for (int space = 0; space <= n - i; space++)
        {
            cout << "   ";
        }

        // loop to print *
        for (int j = 1; j <= i * 2 - 1; j++)
        {
            cout << " * ";
        }

        cout << "\n";
    }

    return 0;
}
```
</details>

---

### Pattern 5

input : 5
```
        *
      *   *
    *       *
  *           *
*               *
```

<details> <summary>Show Solution</summary>  

Solution by : [@your_name](github_account_url)

```C++
#include <iostream>
using namespace std;

int main()
{
    int n = 5;
    // loop for line number of lines
    for (int i = 1; i <= n; i++)
    {
        // loop to print leading spaces in each line
        for (int space = 0; space <= n - i; space++)
        {
            cout << "   ";
        }
        for (int j = 1; j <= i * 2 - 1; j++)
        {

            if (j == 1 || (j == i * 2 - 1))
            {
                cout << " * ";
            }
            else
            {
                cout << "   ";
            }
        }

        cout << "\n";
    }

    return 0;
}

```
</details>

---

### Pattern 6

input : 6
```
        *
      * * *
    *   *   *
  *     *     *
*       *       *
```

<details> <summary>Show Solution</summary>  

Solution by : [@your_name](github_account_url)

```C++
#include <iostream>
using namespace std;

int main()
{
    int n = 5;
    // loop for line number of lines
    for (int i = 1; i <= n; i++)
    {
        // loop to print leading spaces in each line
        for (int space = 0; space <= n - i; space++)
        {
            cout << "   ";
        }
        for (int j = 1; j <= i * 2 - 1; j++)
        {

            if (j == 1 || (j == i * 2 - 1) || j == i)
            {
                cout << " * ";
            }
            else
            {
                cout << "   ";
            }
        }

        cout << "\n";
    }

    return 0;
}
```
</details>

---

### Pattern 7

input : 5
```
* * * * * * * * *
  * * * * * * *
    * * * * *
      * * *
        *
```

<details> <summary>Show Solution</summary>  

Solution by : [@your_name](github_account_url)

```C++

#include <iostream>
using namespace std; // include stdio.h

int main()
{
    int n = 5;

    // loop for line number of lines
    for (int i = n; i >= 1; i--)
    {
        // loop to print leading spaces in each line
        for (int space = n - i; space >= 1; space--)
        {
            cout << "   ";
        }

        // loop to print *
        for (int j = i * 2 - 1; j >= 1; j--)
        {
            cout << " * ";
        }

        cout << "\n";
    }

    return 0;
}
```
</details>

---

### Pattern 8

input : 7
```
*
* //
* // @
* // @ *
* // @ * //
* // @ * // @
* // @ * // @ *
```

<details> <summary>Show Solution</summary>  

Solution by : [@your_name](github_account_url)

```C++

```
</details>

---

### Pattern 9

input : 4
```
* * * *
 * * *
  * *
   *
  * *
 * * *
* * * *
```

<details> <summary>Show Solution</summary>  

Solution by : [@your_name](github_account_url)

```C++
// your solution here
```
</details>

---

### Pattern 10

input : 4
```
*
* *
* * *
* * * *
* * *
* *
*
```

<details> <summary>Show Solution</summary>  

Solution by : [@your_name](github_account_url)

```C++
// your solution here
```
</details>

---

### Pattern 11

input : 4
```
*           *
* *       * *
* * *   * * *
* * * * * * *
```

<details> <summary>Show Solution</summary>  

Solution by : [@your_name](github_account_url)

```C++
// your solution here
```
</details>

---

### Pattern 12

input : 4
```
* * * *
* * *
* *
*
* *
* * *
* * * *
```

<details> <summary>Show Solution</summary>  

Solution by : [@your_name](github_account_url)

```C++
// your solution here
```
</details>

---
