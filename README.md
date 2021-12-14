# STARTING OF THE QUIZ #

print("WELCOME TO THE QUIZ")
print("CHECK YOUR BASIC KNOWLEDGE OF PYTHON")
print("It will take only 5-6 minutes")

playing = input(" DO YOU WANT TO PLAY ? ")
print (playing)

if playing.lower() != "yes":
	print("Are you afraid that you will loose??")
	quit()

print("Lets play!!")
score = 0

answer = input("What is the extension for python program?     ")
if answer.lower() == ".py" :
	print("Correct!!")
	score+=1
else:
	print("Incorrect!!")

answer = input("Who developed the python language?     ")
if answer.lower() == "guido van rossum" :
	print("Correct!!")
	score+=1
else:
	print("Incorrect!!")

answer = input("Which character is used for single line comment in python?     ")
if answer == "#" :
	print("Correct!!")
	score+=1
else:
	print("Incorrect!!")

answer = input("In which year python language was developed?     ")
if answer == "1989" :
	print("Correct!!")
	score+=1
else:
	print("Incorrect!!")

answer = input("What is the method inside the class in python language called?     ")
if answer.lower() == "function" :
	print("Correct!!")
	score+=1
else:
	print("Incorrect!!")

answer = input("What will be the output of the expression : 4 + 3 % 5 ?    ")
if answer.lower() == "7" :
	print("Correct!!")
	score+=1
else:
	print("Incorrect!!")

answer = input("What will be the output of following?  \n		i = 1  \n		while True:  \n			if i % 3 == 0  \n				break  \n			print(i)  \n			i + = 1      ")
if answer.lower() == "error" :
	print("Correct!!")
	score+=1
else:
	print("Incorrect!!")

answer = input("What does pip in python stand for?    ")
if answer.lower() == "preferred installer program" :
	print("Correct!!")
	score+=1
else:
	print("Incorrect!!")

answer = input("Which operator is the truncation division operator in Python?    ")
if answer.lower() == "//" :
	print("Correct!!")
	score+=1
else:
	print("Incorrect!!")

answer = input("What built-in function is used to print something in python?    ")
if answer.lower() == "print()" :
	print("Correct!!")
	score+=1
else:
	print("Incorrect!!")

print("Your scores are = " + str(score))
print("Your percentage = " + str((score/10) * 100))

print("Thank you for your time")
print("IT'S THE TIME FOR FEEDBACK NOW")

feedback = input("DO YOU LIKE THE QUIZ ?  ")
print(feedback)

if feedback.lower() != "yes":
	print("It's ok!! Thank you for your feedback!! I'll try to make it better!! ")
	quit()

if feedback.lower() == "yes":
	print("Thank you for your feedback!! ")

store = input("Could you please tell what do you like about this quiz?? \n")

#END OF THE QUIZ#
