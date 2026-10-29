[sales tax.py](https://github.com/user-attachments/files/34153473/sales.tax.py)
# sales-taxprice = float(input("Enter the price of the sale item:"))  
state = input("Enter the state being shipped to:").upper() 

if state == "TX" or state == "LA":
    shipping_tax = 1.25  
elif state == "CA": 
    shipping_tax = 3.25 
else: 
    shipping_tax = 0.50 

print("The shipping tax for", state, "is $", shipping_tax)
