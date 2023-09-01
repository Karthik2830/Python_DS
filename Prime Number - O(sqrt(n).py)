Prime number using square root
Given a positive integer N, check if the number is a prime or not.

Constraint: 1 < N < 10^6
Example 1:
Input:
11
Output:
The given number is a prime number.
Example 2:
Input:
15
Output:
Given number is not a prime number
""code starts here """
import math
def is_prime(n):
    if n <= 1:
        return False
    if n == 2:
        return True
    if n % 2 == 0:
        return False 
    for i in range(3, int(math.sqrt(n)) + 1, 2):
        if n % i == 0:
            return False    
    return True
N = int(input(""))
if 1 < N < 10**6:
    if is_prime(N):
        print("Given number is a prime number")
    else:
        print("Given number is not a prime number")
else:
    print("Please enter a positive integer within the range 1 < N < 10^6.")


