# hw_2.1.2
### 1. Оператор присваивания (=)

let x = 5; // Assign the value 5 to variable x


### 2. Арифметические операторы

let sum = 10 + 5; // Addition
let difference = 10 - 5; // Subtraction
let product = 10 * 5; // Multiplication
let quotient = 10 / 5; // Division
let remainder = 10 % 3; // Modulus
let increment = 5++; // Increment (increase by 1)
let decrement = 5--; // Decrement (decrease by 1)


### 3. Операторы сравнения

let isEqual = (x === y); // Strict equality
let isNotEqual = (x !== y); // Strict inequality
let greaterThan = (x > y); // Greater than
let lessThan = (x < y); // Less than
let greaterOrEqual = (x >= y); // Greater than or equal
let lessOrEqual = (x <= y); // Less than or equal


### 4. Логические операторы

let andOperator = (x && y); // Logical AND (returns true if both values are true)
let orOperator = (x || y); // Logical OR (returns true if at least one value is true)
let notOperator = !x; // Logical NOT (inverts the value)


### 5. Тернарный оператор

let result = (condition) ? trueValue : falseValue; // Ternary operator


### 6. Операторы присваивания с арифметикой

x += y; // Same as x = x + y;
x -= y; // Same as x = x - y;
x *= y; // Same as x = x * y;
x /= y; // Same as x = x / y;
x %= y; // Same as x = x % y;


### 7. Операторы типов данных

let typeOfX = typeof x; // Returns the data type of variable x

### 8. Оператор условного выполнения (if-else)

if (condition) {
  // Executes if the condition is true
} else {
  // Executes if the condition is false
}

### 9. Оператор switch

switch (expression) {
  case value1:
    // Executes if expression is equal to value1
    break;
  case value2:
    // Executes if expression is equal to value2
    break;
  default:
    // Executes if none of the values match
}

### 10. Операторы битовых операций (например, & (И), | (ИЛИ), ^ (Исключающее ИЛИ), ~ (Побитовое НЕ))

let bitwiseAnd = x & y;
let bitwiseOr = x | y;
let bitwiseXor = x ^ y;
let bitwiseNot = ~x;

### Динамическая типизация данных
Динамическая типизация данных в языке программирования означает, что тип переменной определяется во время выполнения программы, а не на этапе компиляции. В JavaScript переменные не связаны с определенным типом данных, и их тип может изменяться в процессе выполнения программы.

Пример кода с использованием динамической типизации в JavaScript:
let dynamicVariable = 5.24;
console.log(dynamicVariable);
dynamicVariable = "New Value";
console.log(dynamicVariable);

В этом примере переменная dynamicVariable сначала содержит число с плавающей точкой, а затем перезаписывается строковым значением.

Еще пример динамической типизации:
let dynamicVariable = "My Dear Friends!";
console.log(dynamicVariable);
dynamicVariable = 55;
console.log(dynamicVariable);

В данном примере переменная dynamicVariable сначала содержит строковое значение, а затем перезаписывается целочисленным значением