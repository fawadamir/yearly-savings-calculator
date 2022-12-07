# yearly-savings-calculator
name = input("Enter Your Name: ")
print("Hello,", name)
print("welcome to the yearly savings calculator")
monthly_income = input("Please enter your monthly income (PKR): ")
monthly_spending = input("Please enter your montly spending (PKR): ")
yearly_savings = 12* (int(monthly_income) - int(monthly_spending))
print("Dear", name, "your yearly savings are", yearly_savings)
