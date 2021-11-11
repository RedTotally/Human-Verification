# Human-Verification
A simple human verification system

```print("Please do the verification task one by one")

import time
time.sleep(.1)

import random
math = random.randint(0,10)
math_2 = random.randint(0, 10)
math_3 = random.randint(0, 100)
math_4 = random.randint(0, 100)

print(math, "+", math_2)

input_1 = input("Asnwer : ")

if input_1 == str(math + math_2):
    
    print("Checking...")
    
    time.sleep(.2)
    
    print("Step 2/3")
    
    time.sleep(.2)
    
    print(math_3, "+", math_4)
    
    input_2 = input("Answer : ")
    
    if input_2 == str(math_3 + math_4):
        
     print("Checking...")
        
     time.sleep(.2)
        
     print("Step 3/3")
     
     time.sleep(.2)
     
     print("Please type 1-3 in order")
     
     input_3 = input("")
     input_4 = input("")
     input_5 = input("")
     
     time.sleep(.2)
     
     if input_3 == ("1"):
         if input_4 == ("2"):
             if input_5 == ("3"):
                 
                 print("Verify successful")
                 
                 time.sleep(.2)
                 
                 print("Welcome!")
                 
                 print("Generating.")
                 time.sleep(.2)
                 print("Generating..")
                 time.sleep(.2)
                 print("Generating...")
                 
                 number = random.randint(0,10000)
                 
                 print("Your number is: ", number)
                 
     else:
    
                 print("Rejected")
     
    else:
    
     print("Rejected")
    
else:
    
    print("Rejected")
