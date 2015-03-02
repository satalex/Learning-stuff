import datetime
try:
    b_year = int(raw_input('Enter your birth year: '))
    b_month = int(raw_input('Enter your birth month: '))
    b_day = int(raw_input('Enter your birth day: '))
except:
    print "Come on! Do you even can't enter numbers?"
    print "Hit Enter and try again from start"
    raw_input()
    exit ()
birth = datetime.date(b_year, b_month, b_day)
today = datetime.date.today()
dayslived = today - birth
doubledate = today + dayslived
doubleage = doubledate.year - birth.year
print ''
print 'Today you', dayslived.days, 'days old'
if dayslived.days >= 11000:
    print 'Wow, you old!'
    print 'I mean REALLY old'
    print 'if you will have lived another', dayslived.days, 'days, it will be', doubledate, 'and you will be', doubleage,"!" 
    print "I'm not sure if people can live so long"
else:
    print "You're in awesome age!"
    print 'Everything good is ahead for you'
    print 'Even when you will have lived another', dayslived.days, 'days, you will be only', doubleage, 'kiddo'
raw_input()
