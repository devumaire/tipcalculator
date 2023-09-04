print("Welcome to the tip calculator.")
total_bill =float((input("What was the total bill? $")))
tip_percentage = int(input("what percentage tip would you like to give? 10,12 or 15 " ))
number_people = str(input("How many people to split the bill?"))
calculation =  total_bill * (tip_percentage/100)
per_person = calculation + total_bill
print(f"Each person should pay: ${per_person:.2f}")

