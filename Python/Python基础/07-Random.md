# Random

```python
import random

n = random.randint(0, 100)

user_guess = int(input("input your guess : "))

if user_guess > n:
    print("try smaller")
elif user_guess < n:
    print("try bigger")
else:
    print("Bingo ,you get it")

print(n)

```

# Type



# Format

```python
s = "Welcome {name} , You're a {job} "
print(s.format(name = "Eva", job = "Student")) 
#输出 Welcome Eva , You're a Student 
```

