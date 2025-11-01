def is_prime(n):
    if n < 2:
        return False
    for i in range(2, int(n**0.5) + 1):
        if n % i == 0:
            return Fals
    return True

if __name__ == "__main__":
    num = 29
    print(f"Is {num} a prime number? {is_prime(num)}")
