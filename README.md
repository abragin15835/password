import random

symvols = "+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"

length_password = int (input('Enter password length'))

password = ""

for i in range (length_password):
    password += random.choic1e (symvols)

print (password)
