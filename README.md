# Python

print("Welcome to your virtual lemonade stand.")
Day = 1
print("You have 5 days to make as much money as you can.")
while Day < 6:
    
  print("\nDay " + str(Day))
  
  Lemons = int(input("\nHow many lemons do you want? "))
  priceOfLemon = int(input("What is the price of lemons? "))
  priceOfSugar = int(input("What is the price of sugar? "))
  totalCost = (Lemons * priceOfLemon) + priceOfSugar
  print("The cost of the ingredients is $" + str(totalCost) + ".")
  costPerCupOfLemonade = int(input("What is the cost of each cup of lemonade? "))
  cupsSold = int(input("How many cups do you want to sell? "))
  moneyMade = costPerCupOfLemonade * cupsSold
  totalProfit = moneyMade - totalCost
  print("Your profit is $" + str(totalProfit) + ".")

  isProfit = totalProfit > 0
  print("Did you make profit?")
  print(isProfit)
  Day = Day+1


print("Game over, you can add your total profits to see how much money you have made.")


