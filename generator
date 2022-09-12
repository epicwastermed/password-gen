import random
import string
# -- Arrays/Lists - Variables - Printing - User Input ifs and else\elifs - imports -- Loops - F Strings
# -- Project 1: Pull a random letter from a list holding the alphabet and print three times using a for loop - Check!!!
# -- Project 2: Print a list of names print all of them but say their name then a random job - Example: Joe works at maccas - Check!!!
# -- Project 3: Password generator but user inputs how long they want and if they want special characters (!@#$%^&*()_+?><:)
ascii = list=(string.ascii_letters + string.digits + "!@#$%^&*()")
scii = list=(string.ascii_letters + string.digits)  




question = input("Do you want special characthers in your password?: ")
if question == 'yes' or 'Yes':
	
		## length of password from the user
	length = int(input("Enter password length: "))
	
	
	password = []
	for i in range(length):
		password.append(random.choice(ascii))


	
	print("".join(password))

elif question == 'no' or 'No':
	## length of password from the user
	length = int(input("Enter password length: "))


	password = []
	for i in range(length):
		password.append(random.choice(scii))


	
	print("".join(password))
