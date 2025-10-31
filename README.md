# daily_update.py
import datetime
import random

print("Daily GitHub activity - Day 22")

numbers = [random.randint(1, 50) for _ in range(7)]
max_number = max(numbers)
today = datetime.date.today()

print(f"Today's date: {today}")
print(f"Generated numbers: {numbers}")
print(f"The largest number is: {max_number}")
