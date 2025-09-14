# Calculator-
Calculator (basic)
function add(a, b) {
  return a + b;
}
function subtract(a, b) {
  return a - b;
}
function multiply(a, b) {
  return a * b;
}
function divide(a, b) {
  return b !== 0 ? a / b : "Cannot divide by zero";
}

console.log(add(5, 3));       // 8
console.log(subtract(10, 4)); // 6
console.log(multiply(2, 6));  // 12
console.log(divide(8, 2));    // 4
