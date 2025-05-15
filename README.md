''' program to determine the character entered by a user ,whether 
it is an alphabet, digit or space by using seperate if condition 
and predefined string functions'''
char= input("press any key:")
if char.isalpha():
    print("the user hqas entered character")
if char.isdigit():
    print("the user has entered digit")
if char.isspace():
    print("the user has entered space")
