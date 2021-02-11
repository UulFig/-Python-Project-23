# -Python-Project-23
#23 If is a prime number

def prime_checker(number):
    is_prime = True
    for i in range(2, number):
        if number % i == 0:
            is_prime = False
    if is_prime:
         print("It's a prime number")
    else:
        print("It's not a prime number")

prime_checker(int(input("Put a number: ")))
