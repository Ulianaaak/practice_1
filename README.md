# practice_1
number = int(input("Enter the integer number: ")) 
re_number = 0
while (number > 0): 
    remainder = number % 10 
    re_number = (re_number * 10) + remainder 
    number = number // 10 
print("The reverse number is : {} ".format(re_number))
