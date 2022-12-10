#Python-QUIZ-application
#simple code to understand the quiz application using python ( Jupyter ) 

#convert the 0 into a number so we can add scores
score =0
score =int(score)

print("welcome to Wedneday quiz")

playing = input("Do u want to play ?")

if playing !="yes":

    quit()

    print("okay! Let's play! \n Choose the correct answers for the given options \n Best of Luck!")
else:
    print("INVALID INPUT")

answer = input("who's the USA president?: \n A) Luthas B) Donald J trump C) Joe biden D) Marcus. [A/B/C/D]?:")

if answer == "C":
    print('correct')
    score = score + 1
else:
    print("Incorrect!")

print("Your current score is " + str(score) + " out of 7")

answer = input("who's the president of our india 2022?: \n A) N modi B) Donald J trump C) Luthas D) Marcus. [A/B/C/D]?:")
if answer == "A":
    print('correct')
    score = score + 1
else:
    print("Incorrect!")
    
print("Your current score is " + str(score) + " out of 7")

answer = input("what's the value of 18*2+6-4? A)25 B)47 C)57 D)38. [A/B/C/D]?: ")
if answer == "D":
    print('correct')
    score = score + 1 
else:
    print("Incorrect!")
    
print("Your current score is " + str(score) + " out of 7")

answer = input("What was Meta Platforms Inc formerly known as? A)fb B)insta C)snap D)Tesla. [A/B/C/D]?:")
if answer == "A":
    print('correct')
    score = score + 1
else:
    print("Incorrect!")

print("Your current score is " + str(score) + " out of 7")

answer = input("Which English city is known as the Steel City? A)Shie fied B)shieffield C)NA D)Both A and B. [A/B/C/D]? ")

if answer == "B":
    print('correct')
    score = score + 1
else:
    print("Incorrect!")

print("Your current score is " + str(score) + " out of 7")

answer = input("Which former British colony was given back to China in 1997? A)USA B)IND C)TNZ D)UK. [A/B/C/D]?")
if answer == "D":
    print('correct')
    score = score + 1 
else:
    print("Incorrect!")
    
print("Your current score is " + str(score) + " out of 7")
    
answer = input("Which element is said to keep bones strong? A)Ca B)mg C)K D)Cr. [A/B/C/D]?: ")
if answer == "A":
    print('correct')
    score = score + 1
else:
    print("Incorrect!")
    
print("Your current score is " + str(score) + " out of 7")
    
