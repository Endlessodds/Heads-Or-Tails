import random
import time

flip = int(input("Insert the number of flips: "))

head = 0
tail = 0

while flip != 0:
    if random.randint(0,1) == 0:
        print("Head")
        flip = flip - 1
        head += 1
    else:
        print("Tail")
        flip = flip - 1
        tail += 1

for x in range(3,0,-1):
    time.sleep(1)
    print(x)
    
print(f"\nYou got {head} heads and {tail} tails!")

#check out a simpler version of Heads or Tails in main_2
