# Day_5-py
# My python learning journey
my_name=input("Enter your name:")
his_name=input("Enter his name:")
my_name=my_name.lower()
his_name=his_name.lower()
full_name=my_name+his_name
#counting love marks
count_t= full_name.count("t")
count_r=full_name.count("r")
count_u=full_name.count("u")
count_e=full_name.count("e")
count_true=count_t+count_r+count_u+count_e
count_l=full_name.count("l")
count_o=full_name.count("o")
count_v= full_name.count("v")
count_e=full_name.count("e")
count_love=count_l+count_o+count_v+count_e
love_mark=count_true+count_love
print(f"Your love mark is {love_mark}")
