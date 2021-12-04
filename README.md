# VariableDeclarationApex

Integer p = 10;
Integer y = 3;
decimal r = 1.2;
system.debug('Principal is :'+p);
system.debug('time in year is :'+y);
system.debug('rate is :'+r);
decimal si = (p*r*y)/100 ;
system.debug('simple intrest is :'+si);


Date newDate = Date.newInstance(2021, 09, 7);
System.debug('Date is : '+newDate);
Date todayDate = Date.today();
System.debug('Todays Date is : '+todayDate); 
Date newDate1 = todayDate.addYears(2);
System.debug('Date after 2 years from today is:'+newDate1);
Date newDate2 = todayDate.addMonths(2);
System.debug('Date after 2 months from today is:'+newDate2);
Date date1 = Date.newInstance(2021, 11, 20);
System.debug('Date 1 is : '+date1);
Date date2 = Date.newInstance(2021, 12, 24);
System.debug('Date 2 is : '+date2);
Integer daysdue = date1.daysBetween(date2);
System.debug('Days b/w date2 and date1 are:'+daysdue);
