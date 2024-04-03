// Task 1
int addTwo(int a, int b) {
  return a + b;
}

// Task 2
int subtractTwo(int a, int b) {
  return a - b;
}

// Task 3
int multiplyTwo(int a, int b) {
  return a * b;
}

// Task 4
double divideTwo(int a, int b) {
  if (b == 0) {
    throw ArgumentError('Cannot divide by zero');
  }
  return a / b;
}

// Task 5
int stringLength(String str) {
  return str.length;
}

// Task 6
dynamic getFirstElement(List list) {
  if (list.isEmpty) {
    throw ArgumentError('List is empty');
  }
  return list[0];
}

void main() {
  // Testing the functions
  print('Task 1: addTwo(15, 8) = ${addTwo(15, 8)}');
  print('Task 2: subtractTwo(20, 9) = ${subtractTwo(20, 9)}');
  print('Task 3: multiplyTwo(7, 4) = ${multiplyTwo(7, 4)}');
  print('Task 4: divideTwo(36, 6) = ${divideTwo(36, 6)}');
  print('Task 5: stringLength("Dart") = ${stringLength("Dart")}');
  print('Task 6: getFirstElement([15, 20, 25]) = ${getFirstElement([15, 20, 25])}');
}
