## NHS Number validator and Generator

Built with Intersystems Cache ObjectScript

### input()
Prompts the user to enter an NHS number. Returns "Valid" if valid number

### validate(n)
Validates a given number n 

### generator()
Generates a list of NHS numbers between a specific range. Stores them in global array called ^validNums

### random()
Returns a random NHS number between currently used ranges (4000000000 - 4999999999 and 6000000000 - 7088000001)

### printValid()
Retrieves all items from ^validNums global array