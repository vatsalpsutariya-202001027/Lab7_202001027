
# Lab7_202001027


## Section A:

### Test Cases:

| Test Case Id  | Day | Month | Year | Expected Output (DD/MM/YY) |
|-|-|-|-|-|
|1|5|5|2010|4/5/2010|
|2|19|12|2002|18/12/2002|
|3|1|6|1999|31/5/1999|
|4|24|7|2013|23/7/2013|
|5|1|5|2005|30/4/2005|
|6|1|3|2009|28/2/2009|
|7|1|1|2001|31/12/2000|
|8|29|2|2003|Invalid Date|
|9|31|4|2008|Invalid Date|


### Equivalence Class Testing:

#### Input Classes:
```
Day:
D1: Day between 1 to 28
D2: 29
D3: 30 
D4: 31

Month:
M1: Month has 30 days
M2: Month has 31 days
M3: Month is February

Year:
Y1: Year is a leap year
Y2: Year is a normal year 
```

#### Output Classes:
```
Decrement Day
Reset Day and Decrement Month
Decrement Year
Invalid Date
```
### Strong Normal Equivalence Class Test Cases:
