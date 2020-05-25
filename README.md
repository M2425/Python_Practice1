# Python_Practice1
#practicepython.org
#Exercise1:


name = input("enter your name please!\n")
age = int(input('Enter your age please!\n'))

from datetime import datetime

todayYear = datetime.today()

hundredthYear = (100 - age) + todayYear.year

print(f"Hello {name}, you will be 100 year old in the year {hundredthYear}")
