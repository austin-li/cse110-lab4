1. num1, num2, and result are all strings since .value() returns a string, so calculateSum is doing string concatenation instead of addition
2. I would convert the string to a number using Number()
