# verify-then-enter
#I just started learning python and its a code that ask users name and age and also ask if they have corona or not to enter the building
print('Enter your name')
name=input("")
print('Enter your age')
age=input("")
print('Do you have corona yes/no')
corona=input('')
if corona=="yes" :
    print(f"{name} can't enter the building")
else :
    print(f"{name} can enter the building")
