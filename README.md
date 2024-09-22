# Chatbot
print('Welcome to Elite 101 chatbot'); 
print('What is your name?'); 
name = input();
print('And your age?')
age = input();
if age.isnumeric():
  age=int(age) 
else:
  print('Please enter a valid age')
  age = input();
  age=int(age)

print('---------------------------------');
print('Hello ' + name + '! You seem to be ' + str(age) + ' years old. How can I help you today?');
print('---------------------------------');

# Menu 
print('Menu:');
print('1. place holder 1');
print('2. place holder 2');
print('3. place holder 3');
print('4. Exit conversation');
choice = input('Please enter your choice in number: '); 
               
if choice == '1': 
  print('placeholder 1 - you selected option 1');
elif choice == '2':
  print('placeholder 2 - you selected option 2');
elif choice == '3':
  print('placeholder 3 - you selected option 3');
elif choice == '4':
  print('Exiting conversation');
  print('Thank you for using Elite 101 chatbot. Have a great day!')
  exit()
else:
  print('invalid choice');
  
