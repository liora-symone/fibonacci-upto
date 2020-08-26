# fibonacci-upto
This code prints the Fibonacci sequence up to a given input value, n.

# Fibonacci numbers function
def fibonacci(n):
    
    i = 0
    
# Condition 1: A number less than 1 is the input.
    if n <= 0:
        print("Please enter an integer greater than 0.")
# Condition 2: 1 is the input.        
    elif n == 1:
        print("Fibonacci sequence:")
        print(fibnumbers[0])
        print(fibnumbers[1])
        print(fibnumbers[1])
# Condition 3: A number greater than 1 is the input.        
    else:
        print("Fibonacci sequence:")
        while fibnumbers[i] <= n:
            fibnumbers.append(fibnumbers[i]+fibnumbers[i+1])
            print(fibnumbers[i])
            i += 1

fibonacci(n)
# calling the function
