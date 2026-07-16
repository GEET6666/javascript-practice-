Q1. What is the output of the following Python expression?

```python
print(type(1 / 2))
Answer: B) <class 'float'>
Q2. Explain the difference between a tuple and a list in Python. Provide a brief code snippet demonstrating when you would use one over the other.

A list is mutable, so its elements can be changed. A tuple is immutable, so its elements cannot be changed after creation.

```python
# List: used when data may change
fruits = ["apple", "banana"]
fruits.append("mango")

# Tuple: used for fixed data
coordinates = (10, 20)
Q3. What will be the output of the following Python code?

```python
my_dict = {"a": 1, "b": 2, "c": 3}
print(my_dict.get("d", 4))
Answer: 4
Q4. Write a Python function called `is_palindrome(word)` that takes a string as input and returns `True` if the word is a palindrome, and `False` otherwise. (Ignore case sensitivity.)

```python
def is_palindrome(word):
    word = word.lower()
    return word == word[::-1]
Example: print(is_palindrome("Madam"))
Output:
True
Q5. Analyze the following loop. How many times will the word "Hello" be printed?
count = 0

while count < 5:
    print("Hello")
    count += 2
Answer: 3 times
Q6. Given the list numbers = [1, 2, 3, 4, 5, 6], write a list comprehension that generates a new list containing only the squares of the even numbers.
numbers = [1, 2, 3, 4, 5, 6]

squares_of_evens = [x**2 for x in numbers if x % 2 == 0]

print(squares_of_evens)
Output:
[4, 16, 36]
Q7. Explain the use of the with statement in Python for file handling.
with open("file.txt", "r") as file:
    data = file.read()
Q8. Write a Python program to find and print the largest element in an array/list of integers without using the built-in max() function.
numbers = [12, 45, 2, 89, 34, 11]

largest = numbers[0]

for num in numbers:
    if num > largest:
        largest = num

print("Largest element is:", largest)
Output:
Largest element is: 89
Q9. Which HTML5 tag is used to define semantic navigation links on a website?
Answer: <nav>.
Q10. Create a valid HTML form code block that contains a text input field for a user's “Username”, a password input field, and a submit button. Ensure all inputs are properly labeled using the <label> element.
HTML
<form action="/submit" method="POST">
  <div>
    <label for="username">Username:</label>
    <input type="text" id="username" name="username" required>
  </div>

  <br>

  <div>
    <label for="password">Password:</label>
    <input type="password" id="password" name="password" required>
  </div>

  <br>

  <button type="submit">Submit</button>
</form>
Q11. What is the difference between block-level elements and inline elements in HTML? Provide two examples of each.
Answer:
Block-level elements start on a new line and take up the full available width.
Examples: <div>, <p>
Inline elements do not start on a new line and take up only the required width.
Examples: <span>, <a>
Q12. What attribute must be added to an <img> tag to provide alternative text for visually 
