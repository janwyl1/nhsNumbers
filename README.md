## NHS Number Validator and Generator

Validates NHS Numbers using the Mod 11 Check Digit.

Built with Intersystems Cache ObjectScript. 

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

#### Thanks to:
* [NHS Data Dictionary](https://www.datadictionary.nhs.uk/version2/data_dictionary/data_field_notes/n/nhs_number_de.asp)
* [JS Implementation](https://github.com/spikeheap/nhs-number-validator)
* [Python Implementation](https://github.com/Iain-S/nhs_number_generator/blob/master/generate_nhs_numbers.py)
* [NHS Number Validator/Generator](http://danielbayley.uk/nhs-number/)