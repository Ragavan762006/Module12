# 📚 Stack using Linked List: Check and Print the Index Value of the Elements Stored in the Stack

This Python program demonstrates how to:
1. Create a stack using a list.
2. Add elements to the stack.
3. Print the index and corresponding value of each element in the stack.

## 🎯 Aim

To write a Python program that:
- Creates a stack using a list.
- Adds elements to the stack.
- Prints the index values of the stack elements along with the corresponding values.

## 🧠 Algorithm

1. **Create an Empty Stack**:
   - Initialize an empty list `stack` to store elements.

2. **Add Elements to the Stack**:
   - Append elements (e.g., 'a', 'b', 'c') to the stack using the `append()` method.

3. **Print the Initial Stack**:
   - Print the contents of the stack with a message "Initial stack: ".

4. **Iterate through the Stack**:
   - Use a `for` loop with `range()` to iterate through the stack.
   - Print the index value and corresponding element at that index.

5. **Print Index and Value**:
   - For each element in the stack, print the index and the value at that index.

## 📝 Program
~~~c
stack = []
stack.append(5)
stack.append(10)
stack.append(15)
stack.append(20)
print("Stack contents with index values:")
for index, value in enumerate(stack):
    print(f"Index {index} → Value: {value}")
~~~

## Sample Output

![Screenshot 2025-05-23 120648](https://github.com/user-attachments/assets/dc045f4d-b5f2-4260-a1a0-5f952826ad27)


## Result
Thus the program has been executed sucessfully.
