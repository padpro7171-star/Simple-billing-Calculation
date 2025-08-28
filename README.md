# Simple-billing-Calculation
 A simple Python-based billing system that collects seller and customer details,  takes purchased items and prices, and generates a formatted invoice.

#simple billing system
print("BILLING\n")
print("---Company/seller info---")

#seller contact
place  = input("Enter Address: ")
contact = input("Enter Phone No: ")
id = input("Enter Email id: ")
gstno = input("Enter GSTIN: ")
state = input("Enter State: ")
print("\n")

#customer contact
print("---customer info---")
custbill = input("Enter Bill to: ")
custname = input("Enter name: ")
custplace = input("Enter Address: ")
custcontact = input("Enter contact no: ")
custstate = input("Enter state: ")
cusshipping = input("Enter shipping address: ")
date = input("Enter date: ")
print("\n")
#items and prices
print("---Purchased item---")
item1 = input("Enter item 1: " )
price1 = float(input("Enter price 1: "))

item2 = input("Enter item 2: " )
price2 = float(input("Enter price 2: "))


item3 = input("Enter item 3: " )
price3 = float(input("Enter price 3: "))

#calculation
Total = price1 + price2 + price3 
print("\n")

print("------Company/seller------")
print("Address: ", place)
print("Phone No: ", contact)
print("Email ID: ", id)
print("GSTIN: ", gstno)
print("State: ", state)
print("\n")
print("----------TAX INVOICE----------")
print("Bill To: ", custbill)                               
print("Name: ", custname)
print("Address: ", custplace)
print("Contact No: ", custcontact)
print("State: ", custstate)
print("Shipping To: ", cusshipping)
print("Date: ", date)

#printing bill
print("\n-------BILLING HISTORY-------")
print(f"{item1} :  {price1}")
print(f"{item2} :  {price2}")
print(f"{item3} :  {price3}")
print("------------------------------")
print("TOTAL: ", Total)

print("\n")

print("***************THANK YOU***************")
