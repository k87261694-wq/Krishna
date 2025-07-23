# Krishna# Take input from user
a = int(input("Enter starting number (a): "))
b = int(input("Enter ending number (b): "))
c = int(input("Enter the divisor (c): "))

# Initialize counter
count = 0

# Loop from a to b
for i in range(a, b + 1):
    if i % c == 0:
        count += 1

# Show result
print(f"From {a} to {b}, there are {count} numbers divisible by {c}.")
Divisible
