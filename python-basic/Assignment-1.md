# Ineuron's python basic assignment-1 #


### 1. In the below elements which of them are values or an expression? eg:- values can be
### integer or string and expressions will be mathematical operators.
### *, 'hello', -87.8, -, /, +, 6 

    Solution: Values: 'hello', -87.8 & 6
              Expressions: *, -, / & +

### 2. What is the difference between string and variable?

    Solution: String is a data type & variable is a storage location associated with a value. That value can be string also. 

### 3. Describe three different data types.

    Solution: Just like every programming language, python has various data types. From which, three most commonly used data types are: 
              i) Integers: example 10, 100, 100000 etc. 
              ii) String: 'string', '100', 'Ineuron' etc.
              ii) Complex nos: 5j + 12, 6j + 16
              We can check type of a value using type() function. 
 
### 4. What is an expression made up of? What do all expressions do?

    Solution: Python expression are made up of identifiers, literals, and operators.

### 5. This assignment statements, like spam = 10. What is the difference between an
### expression and a statement?

    Solution: Expression evaluates to a value while statement performs some action. 

### 6. After running the following code, what does the variable bacon contain?
### bacon = 22
### bacon + 1

    Solution: 23 

### 7. What should the values of the following two terms be?
### 'spam' + 'spamspam'
### 'spam' * 3

    Solution: Concatenation will be done. That means, value will be 'spamspamspam'

### 8. Why is eggs a valid variable name while 100 is invalid?

    Solution: Because a variable name cannot start with a number.

### 9. What three functions can be used to get the integer, floating-point number, or string
### version of a value?

    Solution: int(x) to get the integer value, float(x) to get the floating-point nuber and str(x) to get the string version of the given value 'x'.

### 10. Why does this expression cause an error? How can you fix it?
'I have eaten' + 99 + 'burritos.'

    Solution: We will get error because the data type of 99 is integer. For concatenation we should convert it to a string. 
              i.e 'I have eaten' + ' 99 ' + 'burritos' will be the correct approach. 
