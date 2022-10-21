how to run the debugger????
1. The issue is that the numbers are being saved as strings so when you add then it ends up concatenating them instead of adding them.
2. I would make sure the datatypes of num1 and num2 are Numbers instead of strings so that when we do the + operation it will act add them instead of concatenate them.