# C# Operator Precedence

AmieDD www.amiedd.com

```C# runnable

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace MathOperator
{
    class Program
    {
        static void Main(string[] args)
        {
            int x = 4+3*2;
            Console.WriteLine(x);
        }
    }
}
```

# C# Operator Precedence Multiplication

Operator precedence groups terms in expressions. This affects how the math problem is evaluated. Some operators take higher precedence. Example: Multiplication operator has higher precedence over the addition operator.

The above code will output 10
The Multiplication is the higher precedence 3*2 = 6
Then the Addition 4+6
Equals 10
