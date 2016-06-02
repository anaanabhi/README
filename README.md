# README
def is_leap_baby(day,month,year):
    if day == 29:
        if month == 2:
            if year % 100 != 0:
                if year % 4 == 0:
                    return True
            if year % 400 == 0:
                return True
    return False
    
    
  def output(status,name):
    if status:
        print "%s is one of an extremely rare species. He is a leap year baby!" % name
    else:
        print "There's nothing special about %s's birthday. He is not a leap year baby!" % name
