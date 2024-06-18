### 1. `if` Statement

The `if` statement is used to execute a block of code based on a condition.

#### Syntax:

```dart
if (condition) {
  // code to execute if condition is true
} else if (anotherCondition) {
  // code to execute if anotherCondition is true
} else {
  // code to execute if all previous conditions are false
}
```

#### Example:

```dart
void main() {
  int number = 10;

  if (number > 0) {
    print('The number is positive.');
  } else if (number < 0) {
    print('The number is negative.');
  } else {
    print('The number is zero.');
  }
}
```

### 2. `for` Loop

The `for` loop is used to execute a block of code multiple times.

#### Syntax:

```dart
for (initialization; condition; increment/decrement) {
  // code to execute repeatedly
}
```

#### Example:

```dart
void main() {
  for (int i = 0; i < 5; i++) {
    print('Iteration $i');
  }
}
```

### 3. `while` Loop

The `while` loop executes a block of code as long as a specified condition is true.

#### Syntax:

```dart
while (condition) {
  // code to execute repeatedly
}
```

#### Example:

```dart
void main() {
  int count = 0;

  while (count < 5) {
    print('Count is $count');
    count++;
  }
}
```

### 4. `do-while` Loop

The `do-while` loop is similar to the `while` loop, but it ensures that the code block is executed at least once before the condition is checked.

#### Syntax:

```dart
do {
  // code to execute repeatedly
} while (condition);
```

#### Example:

```dart
void main() {
  int count = 0;

  do {
    print('Count is $count');
    count++;
  } while (count < 5);
}
```

### 5. `switch` Statement

The `switch` statement allows a variable to be tested for equality against a list of values, each with its own block of code to execute.

#### Syntax:

```dart
switch (variable) {
  case value1:
    // code to execute if variable == value1
    break;
  case value2:
    // code to execute if variable == value2
    break;
  // more cases as needed
  default:
    // code to execute if variable doesn't match any case
}
```

#### Example:

```dart
void main() {
  String grade = 'B';

  switch (grade) {
    case 'A':
      print('Excellent!');
      break;
    case 'B':
      print('Good job!');
      break;
    case 'C':
      print('Well done.');
      break;
    case 'D':
      print('You passed.');
      break;
    case 'F':
      print('Better luck next time.');
      break;
    default:
      print('Invalid grade.');
  }
}
```

### In Short

- **`if` statement**: Executes code based on a condition.
- **`for` loop**: Repeats code a specific number of times.
- **`while` loop**: Repeats code while a condition is true.
- **`do-while` loop**: Like `while`, but always executes code block at least once.
- **`switch` statement**: Selects code to execute based on the value of a variable.

These control flow statements are fundamental in Dart for managing how code is executed based on conditions and iterations.
