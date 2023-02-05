# IndividualProject2


# Sydney Marrero
# smarrero2@student.gsu.edu

investmentAmount = float(input("Enter the investment amount: "))
AnnualInterestRate = float(input("Enter the annual interest rate: "))
MonthlyInterestRate = AnnualInterestRate / 1200
NumberOfYears = float(input("Enter the years: "))
NumberOfMonths = NumberOfYears * 12
futureInvestmentAmount = investmentAmount * ((1 + MonthlyInterestRate) ** NumberOfMonths)
print("Future investment value is", round(futureInvestmentAmount, 2))


# Sydney Marrero
# smarrero2@student.gsu.edu

subTotal = float(input('Enter the subtotal: '))
gratuityRate = float(input('Enter the gratuity rate: '))

gratuity = subTotal * gratuityRate / 100

total = subTotal + gratuity
print('The gratuity is ',round(gratuity,2),' and the total is ',round(total,2))
