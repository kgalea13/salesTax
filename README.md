# salesTax
#Python

#This program calculates the sales tax of an item you are purchasing.
#Enter in the original amount, as a whole number or a decimal
#Enter in the sales tax as a whole number
#Program will calculate the total amount


initalValue = float(input('Enter the amount of your item: '))
percent = float(input('Enter the sales tax: '))
rate = percent/100

taxPortion = initalValue * rate

totalPrice = initalValue + taxPortion
print('Here is the total amount my item will cost: ', totalPrice)
