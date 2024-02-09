# Falgun Variables

Think of variables as storage boxes for data values.

## Types of Variables in Falgun

Falgun offers a variety of variable types, including:

- `int` - This type is used for storing whole numbers (integers), like 123 or -123.
- `float32` - This type is used for storing numbers with decimal points, like 19.99 or -19.99.
- `string` - This type is used for storing text. For example, "Hello World". Text values are always enclosed in double quotes.
- `bool` - This type is used for storing values that have two states: `true` or `false`.

More about different variable types, will be explained in the `Data Types` chapter.

## Declaring (Creating) Variables
In Falgun, there are three ways to declare a variable:

### 1. Using the `let` keyword along with the type:
To declare a variable, use the `let` keyword, followed by the variable name and its type:

```
let <name> : <type> = <value>
```

### 2. Using only the `let` keyword:
You can also declare a variable with the `let` keyword, followed directly by the variable name and its value:

```
let <name> = <value>
```

### 3. Using the `:=` operator:
You can declare a variable using the `:=` operator, followed by the variable's value:

```falgun
<name> := <value>
```

In both syntax 2 and 3, `<name>` represents the variable's name and `<value>` is the initial value that gets assigned to the variable. The variable's type is automatically determined based on the value.

## Declaring a Variable with an Initial Value
If you already know the value of a variable at the time of declaration, you can declare the variable and assign its value all in one go. Here's how you do it in three different ways:

1. Declaring a variable with a specific type:

```ts
// Declaring a variable with a specific type
let greeting: string = "Hello, World!";

// Declaring a variable and inferring its type from the initial value
let greeting = "Hello, World!";

// Another way to declare a variable and infer its type from the initial value
greeting := "Hello, World!";
```

In all these examples, we declare a variable named greeting and immediately assign the string "Hello, World!" to it.


## Variable Declaration Without Initial Value

In Falgun, all variables are initialized. So, if you declare a variable without an initial value, its value will be set to the default value of its type:

```js
  let num: int;
  let greeting: string;
  let isActive: bool;

  println(num); // 0
  println(greeting); // ""
  println(isActive); // false
```

### Example explained

In this example there are 3 variables `num`, `greeting`, `isActive`.

These variables are declared but they have not been assigned initial values.

By running the code, we can see that they already have the default values of their respective types:

- `num` is `0`
- `greeting` is `""`
- `isActive` is `false`

## Value Assignment After Declaration
It is possible to assign a value to a variable after it is declared. This is helpful for cases the value is not initially known.

```js
let greeting: string;
greeting = "Hello, World!";

println(greeting); // "Hello, World!"
```

`Note` : You can't declare a variable with `<name> :=` or `let <name>;` without giving it an initial value.

