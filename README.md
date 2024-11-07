weekly_allowance = 500
transportation_cost = 100
snacks = 50
school_supplies = 30
total_expense = transportation_cost + snacks + school_supplies
print("Weekly Budget Breakdown:")
print(f"Allowance: PHP {weekly_allowance}")
print(f"Transportation: PHP {transportation_cost}")
print(f"Snacks: PHP {snacks}")
print(f"School Supplies: PHP {school_supplies}")
print(f"Total Expenses: PHP {total_expense}")
if total_expense > weekly_allowance:
    print("Warning: You are over budget!")
   
