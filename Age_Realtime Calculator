import datetime
print("MonkCo."* 21)
print("                                                 Birth Calculator")
Name = str(input("Enter Your Name : "))
y =  datetime.datetime.now().day
x = datetime.datetime.now().year
z = datetime.datetime.now().month
birthyear = int(input("Enter your BirthYear : "))
birthdate = int(input("Enter your BirthDate : "))
birthmonth = int(input("Enter your BirthMonth : "))
month =[31,28,31,30,31,30,31,31,30,31,30,31]
if birthdate > y:
    z = z - 1
    y = y + month[birthmonth-1]
if birthmonth > z:
    x = x-1
    z = z + 12
Calculated_day = y - birthdate;
Calculated_month = z - birthmonth;
Calculated_year = x - birthyear;
print(Name,"your age is ",Calculated_day,"Days",Calculated_month,"Months",Calculated_year,"Years")
