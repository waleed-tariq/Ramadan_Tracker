# Track the ramadan movement through the years
import math
days = range(1,366)

month2days = {

    "January" : days[0:31],
    "February" : days[31:59],
    "March" : days[59:90],
    "April" :days[90:120],
    "May" : days[120:151],
    "June" : days[151:181],
    "July" : days[181:212],
    "August" : days[212:243],
    "September" : days[243:273],
    "October" : days[273:304],
    "November" : days[304:334],
    "December" : days[334:365]

}


loop = True
yearStart = 2019
ramadanStart = 127

while loop:

    print("Enter a year in which you want to find out what month Ramadan will be on (or a 0 to exit): ")
    newYear = int(input())
    if newYear == 0:
        break
    else:
        yearsPassed = newYear-yearStart
        if yearsPassed > 0:
            for x in range(yearsPassed):
                ramadanStart = ramadanStart - 10
                if ramadanStart < 0:
                    ramadanStart = 365+ramadanStart
        else:
            yearsPassed = yearsPassed*(-1)
            for x in range(yearsPassed):
                ramadanStart = ramadanStart + 10
                if ramadanStart >= 365:
                    ramadanStart = 365-ramadanStart
                    ramadanStart = ramadanStart*(-1)

    if ramadanStart in month2days["January"]:
        print("Ramadan is in the month of January in the year " + str(newYear))

    elif ramadanStart in month2days["February"]:
        print("Ramadan is in the month of February in the year " + str(newYear))

    elif ramadanStart in month2days["March"]:
        print("Ramadan is in the month of March in the year " + str(newYear))

    elif ramadanStart in month2days["April"]:
        print("Ramadan is in the month of April in the year " + str(newYear))

    elif ramadanStart in month2days["May"]:
        print("Ramadan is in the month of May in the year " + str(newYear))

    elif ramadanStart in month2days["June"]:
        print("Ramadan is in the month of June in the year " + str(newYear))

    elif ramadanStart in month2days["July"]:
        print("Ramadan is in the month of July in the year " + str(newYear))

    elif ramadanStart in month2days["August"]:
        print("Ramadan is in the month of August in the year " + str(newYear))

    elif ramadanStart in month2days["September"]:
        print("Ramadan is in the month of September in the year " + str(newYear))

    elif ramadanStart in month2days["October"]:
        print("Ramadan is in the month of October in the year " + str(newYear))

    elif ramadanStart in month2days["November"]:
        print("Ramadan is in the month of November in the year " + str(newYear))

    elif ramadanStart in month2days["December"]:
        print("Ramadan is in the month of December in the year " + str(newYear))

    print("\n")

    yearStart = 2019
    ramadanStart = 127
