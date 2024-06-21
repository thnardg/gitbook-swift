---
description: This is a short guide to the basic Swift syntax.
---

# Syntax 101

#### 1. Variables and Data Types

**Variables and Constants**: Variables are declared as `var` and constants as `let`.

```swift
var myVariable = 10
let myConstant = 42
```

**Data Types**: The basic data types in Swift are `Int`, `Double`, `Float`, `String`, `Bool` and `Data`.&#x20;

```swift
var myString: String = "Hello, Swift"
var myInt: Int = 10
var myDouble: Double = 10.0
var isBool: Bool = true
```

#### 2. Operators

* Arithmetic Operators (`+`, `-`, `*`, `/`, `%`)
* Comparison Operators (`==`, `!=`, `>`, `<`, `>=`, `<=`)
* Logical Operators (`&&`, `||`, `!`)

#### 3. **Control Flow**

*   **If Statements**: Basic conditional logic.

    <pre class="language-swift"><code class="lang-swift">if a == b {
        print("a is equal to b")
    } else if a == c {
        print("a is equal to c")
    <strong>} else {
    </strong>    print("a is not equal to b or c")
    }
    </code></pre>
*   **Switch Statements**: Handling multiple conditions.

    ```swift
    let fruit = "apple"
    switch fruit {
    case "apple":
        print("It's an apple")
    case "banana":
        print("It's a banana")
    default:
        print("Unknown fruit")
    }
    ```
*   **Loops**: `for`, `while`, and `repeat-while` loops.

    ```swift
    for i in 1...5 {
        print(i)
    }
    ```

#### 4. **Functions**

*   Defining and calling functions.

    ```swift
    func greet(name: String) -> String {
        return "Hello, \(name)!"
    }

    let greeting = greet(name: "John")
    ```

#### 5. **Optionals**

*   Understanding and safely unwrapping optionals using `?`, `!`, and `if let`.

    ```swift
    var optionalString: String? = "Hello"
    if let unwrappedString = optionalString {
        print(unwrappedString)
    }
    ```

#### 6. **Collections**

*   **Arrays**: Ordered collections.

    ```swift
    var array = [1, 2, 3, 4, 5]
    ```
*   **Dictionaries**: Key-value pairs.

    ```swift
    var dictionary = ["key1": "value1", "key2": "value2"]
    ```

#### 7. **Classes and Structs**

*   **Classes**: Reference types.

    ```swift
    class Person {
        var name: String
        init(name: String) {
            self.name = name
        }
    }
    ```
*   **Structs**: Value types.

    ```swift
    struct Point {
        var x: Int
        var y: Int
    }
    ```

