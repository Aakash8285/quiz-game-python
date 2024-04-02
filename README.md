
print("Welcome to the Game:")

playing = input("Do you want to play? ")

if playing != "yes":
    quit()
    
print("Okay! Let's play :) ")
score = 0

 
answer = input("Q1: What does CPU stands for? ")
if answer.lower() == "central processing unit":
    score += 1
    print('correct!')
else:
    print("Incorrect!")
    
answer = input("Q2: What does GPU stands for? ")
if answer.lower() == "graphical processing unit":
    score += 1
    print("correct!")
else:
    print("Incorrect!")

answer = input("Q3:What does RAM stands for? ")
if answer.lower() == "random access memory":
    score += 1
    print("correct!")
else:
    print("Incorrect!")
    
answer = input("Q4: What does PSU means? ")
if answer.lower() == "power supply unit":
    score += 1
    print("correct!")
else:
    print("Incorrect!")
    
answer = input("Q5: capital of india? ")
if answer.lower() == "delhi":
    score += 1
    print("correct!")
else:
    print("Incorrect!")
    
    print("you got " + str(score) + " questions correct")
