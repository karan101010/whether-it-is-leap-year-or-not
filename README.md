# whether-it-is-leap-year-or-not
# WRITE A PROGRAM TO CHECK WHETHER IS LEAP YEAR OR NOT AND TAKES THE INPUT FROM THE USER.
year=int(input("Enter the Year"))
if (year%4 == 0):
     print("It is  a leap year")
elif (year%249 == 0):
     print("It is not a leap year")
else:
     print("It is not a leap year")
