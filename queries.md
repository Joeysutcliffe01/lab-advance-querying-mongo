![Ironhack Logo](https://i.imgur.com/1QgrNNw.png)

# Answers

### 1. All the companies whose name match 'Babelgum'. Retrieve only their `name` field.

name: "Babelgum"

### 2. All the companies that have more than 5000 employees. Limit the search to 20 companies and sort them by **number of employees**.

name:"Siemens"
name:"IBM"
name:"Toyota"
name:"PayPal"
name:"Nippon Telegraph and Telephone Corporation"
name:"Samsung Electronics"
name:"Accenture"
name:"Tata Consultancy Services"
name:"Flextronics International"
name:"Safeway"

### 3. All the companies founded between 2000 and 2005, both years included. Retrieve only the `name` and `founded_year` fields.

\_id:52cdef7c4bab8bd675297d8d
name:"Digg"
founded_year:2004
\_id:52cdef7c4bab8bd675297d8e
name:"Facebook"
founded_year:2004
\_id:52cdef7c4bab8bd675297d95
name:"StumbleUpon"
founded_year:2002
\_id:52cdef7c4bab8bd675297d96
name:"Gizmoz"
founded_year:2003
\_id:52cdef7c4bab8bd675297da1
name:"Plaxo"
founded_year:2002
\_id:52cdef7c4bab8bd675297da5
name:"Technorati"
founded_year:2002
\_id:52cdef7c4bab8bd675297da7
name:"AddThis"
founded_year:2004
\_id:52cdef7c4bab8bd675297dac
name:"Veoh"
founded_year:2004
\_id:52cdef7c4bab8bd675297db2
name:"Meetup"
founded_year:2002
\_id:52cdef7c4bab8bd675297db8
name:"SmugMug"
founded_year:2002
\_id:52cdef7c4bab8bd675297dbc
name:"Skype"
founded_year:2003
\_id:52cdef7c4bab8bd675297dc3
name:"Pando Networks"
founded_year:2004
\_id:52cdef7c4bab8bd675297dc6
name:"Ikan"
founded_year:2003
\_id:52cdef7c4bab8bd675297dc7
name:"delicious"
founded_year:2003
\_id:52cdef7c4bab8bd675297dc8
name:"Topix"
founded_year:2002
\_id:52cdef7c4bab8bd675297dc9
name:"Jobster"
founded_year:2004
\_id:52cdef7c4bab8bd675297dcc
name:"AllPeers"
founded_year:2004
\_id:52cdef7c4bab8bd675297dda
name:"iContact"
founded_year:2003
\_id:52cdef7c4bab8bd675297ddc
name:"blinkx"
founded_year:2004
\_id:52cdef7c4bab8bd675297de0
name:"Yelp"
founded_year:2004

### 4. All the companies that had a Valuation Amount of more than 100.000.000 and have been founded before 2010. Retrieve only the `name` and `ipo` fields.

{founded_year: { $lt: 2010, ipo: $gt: 100.000.000}}

### 5. All the companies that have less than 1000 employees and have been founded before 2005. Order them by the number of employees and limit the search to 10 companies.

\_id:52cdef7c4bab8bd675297d8e
name:"Facebook"
\_id:52cdef7c4bab8bd675297d9b
name:"eBay"
\_id:52cdef7c4bab8bd675297da2
name:"Cisco"
\_id:52cdef7c4bab8bd675297da3
name:"Yahoo!"
\_id:52cdef7c4bab8bd675297dba
name:"Google"
\_id:52cdef7c4bab8bd675297dc4
name:"Intel"
\_id:52cdef7c4bab8bd675297e0c
name:"LinkedIn"
\_id:52cdef7c4bab8bd675297e49
name:"Nintendo"
\_id:52cdef7c4bab8bd675297e4d
name:"NetSuite"
\_id:52cdef7c4bab8bd675297e5d
name:"Adobe Systems"
\_id:52cdef7c4bab8bd675297e6f
name:"Sony"
\_id:52cdef7c4bab8bd675297e89
name:"PayPal"
\_id:52cdef7c4bab8bd675297e8e
name:"The Walt Disney Company"
\_id:52cdef7c4bab8bd675297e96
name:"AOL"
\_id:52cdef7c4bab8bd675297ee9
name:"Sun Microsystems"
\_id:52cdef7c4bab8bd675297efe
name:"Zappos"
\_id:52cdef7c4bab8bd675297f19
name:"ReachLocal"
\_id:52cdef7c4bab8bd675297fc2
name:"Nokia"
\_id:52cdef7c4bab8bd675297fcb
name:"Rakuten"
\_id:52cdef7c4bab8bd675297fcd
name:"ValueClick"

<!-- Your Code Goes Here -->

### 6. All the companies that don't include the `partners` field.

<!-- Your Code Goes Here -->

### 7. All the companies that have a null type of value on the `category_code` field.

\_id:52cdef7c4bab8bd6752980f6
name:"Collective"
\_id:52cdef7c4bab8bd675298225
name:"Snimmer"
\_id:52cdef7c4bab8bd675298226
name:"KoolIM"
\_id:52cdef7c4bab8bd675298261
name:"Level9 Media"
\_id:52cdef7c4bab8bd675298262
name:"VidKing"
\_id:52cdef7c4bab8bd67529826e
name:"Drigg"
\_id:52cdef7c4bab8bd675298276
name:"SpaceTime"
\_id:52cdef7c4bab8bd675298279
name:"Touch Clarity"
\_id:52cdef7c4bab8bd67529827a
name:"MMDAYS"
\_id:52cdef7c4bab8bd67529827b
name:"Inside Group"
\_id:52cdef7c4bab8bd67529827e
name:"Repeater Store"
\_id:52cdef7c4bab8bd675298288
name:"Tapesh"
\_id:52cdef7c4bab8bd675298289
name:"iPersians"
\_id:52cdef7c4bab8bd67529828a
name:"NewPersia"
\_id:52cdef7c4bab8bd6752982ab
name:"Pyra Labs"
\_id:52cdef7c4bab8bd6752982b3
name:"Feedmap"
\_id:52cdef7c4bab8bd6752982e0
name:"NuvoMedia"
\_id:52cdef7c4bab8bd6752982e4
name:"Intwine"
\_id:52cdef7c4bab8bd6752982ef
name:"The Weinstein Company"
\_id:52cdef7c4bab8bd6752982f2
name:"ExecuNet"

### 8. All the companies that have at least 100 employees but less than 1000. Retrieve only the `name` and `number of employees` fields.

\_id:52cdef7c4bab8bd675297dbb
name:"Jajah"
number_of_employees:110
\_id:52cdef7c4bab8bd675297dc0
name:"Livestream"
number_of_employees:120
\_id:52cdef7c4bab8bd675297dc1
name:"Ustream"
number_of_employees:250
\_id:52cdef7c4bab8bd675297dda
name:"iContact"
number_of_employees:300
\_id:52cdef7c4bab8bd675297de0
name:"Yelp"
number_of_employees:800
\_id:52cdef7c4bab8bd675297dee
name:"Dailymotion"
number_of_employees:120
\_id:52cdef7c4bab8bd675297df0
name:"RockYou"
number_of_employees:106
\_id:52cdef7c4bab8bd675297e09
name:"Meebo"
number_of_employees:200
\_id:52cdef7c4bab8bd675297e0a
name:"Eventbrite"
number_of_employees:200
\_id:52cdef7c4bab8bd675297e10
name:"Box"
number_of_employees:950
\_id:52cdef7c4bab8bd675297e15
name:"Conduit"
number_of_employees:215
\_id:52cdef7c4bab8bd675297e26
name:"oDesk"
number_of_employees:120
\_id:52cdef7c4bab8bd675297e38
name:"PhotoBox"
number_of_employees:600
\_id:52cdef7c4bab8bd675297e3a
name:"Spreadshirt"
number_of_employees:230
\_id:52cdef7c4bab8bd675297e3c
name:"Bazaarvoice"
number_of_employees:600

\_id:52cdef7c4bab8bd675297e3e
name:"spigit"
number_of_employees:120

### 9. Order all the companies by their IPO price in a descending order.

\_id:52cdef7e4bab8bd67529a8b4
name:"GREE"
ipo:Object
valuation_amount:108960000000
valuation_currency_code:"JPY"
pub_year:2008
pub_month:12
pub_day:17
stock_symbol:"3632"

\_id:52cdef7c4bab8bd675297d8e
name:"Facebook"
ipo:Object
valuation_amount:104000000000
valuation_currency_code:"USD"
pub_year:2012
pub_month:5
pub_day:18
stock_symbol:"NASDAQ:FB"
\_id:52cdef7c4bab8bd675297e7a
name:"Amazon"
ipo:Object
valuation_amount:100000000000
valuation_currency_code:"USD"
pub_year:1997
pub_month:5
pub_day:null
stock_symbol:"NASDAQ:AMZN"
\_id:52cdef7c4bab8bd675297d94
name:"Twitter"
ipo:Object
valuation_amount:18100000000
valuation_currency_code:"USD"
pub_year:2013
pub_month:11
pub_day:7
stock_symbol:"NYSE:TWTR"
\_id:52cdef7d4bab8bd675299d5d
name:"Groupon"
ipo:Object
valuation_amount:12800000000
valuation_currency_code:"USD"
pub_year:2011
pub_month:11
pub_day:7
stock_symbol:"NASDAQ:GRPN"
\_id:52cdef7c4bab8bd675298674
name:"Tencent"
ipo:Object
valuation_amount:11000000000
valuation_currency_code:"USD"
pub_year:2004
pub_month:6
pub_day:16
stock_symbol:"HK:0700"
\_id:52cdef7e4bab8bd67529b996
name:"Western Digital"
ipo:Object
\_id:52cdef7c4bab8bd675297e0c
name:"LinkedIn"
ipo:Object
valuation_amount:9310000000
valuation_currency_code:"USD"
pub_year:2011
pub_month:7
pub_day:20
stock_symbol:"NYSE:LNKD"
\_id:52cdef7c4bab8bd67529859a
name:"BMC Software"
ipo:Object
valuation_amount:6000000000
valuation_currency_code:"USD"
pub_year:1988
pub_month:8
pub_day:12
stock_symbol:"NASDAQ:BMC"
\_id:52cdef7c4bab8bd675298527
name:"Rackspace"
ipo:Object
valuation_amount:5440000000
valuation_currency_code:"USD"
pub_year:2011
pub_month:11
pub_day:7
stock_symbol:"RAX"
\_id:52cdef7c4bab8bd675298760
name:"Baidu"
ipo:Object
valuation_amount:4000000000
valuation_currency_code:"USD"
pub_year:2005
pub_month:8
pub_day:5
stock_symbol:"NASDAQ:BIDU"
\_id:52cdef7c4bab8bd6752981a7
name:"TripAdvisor"
ipo:Object
valuation_amount:3273770000
valuation_currency_code:"USD"
pub_year:2011
pub_month:12
pub_day:21
stock_symbol:"TRIP"
\_id:52cdef7c4bab8bd6752982f6
name:"HomeAway"
ipo:Object
valuation_amount:3000000000
valuation_currency_code:"USD"
pub_year:2011
pub_month:6
pub_day:29
stock_symbol:"NASDAQ:AWAY"
\_id:52cdef7c4bab8bd67529800c
name:"Zillow"
ipo:Object
valuation_amount:2550000000
valuation_currency_code:"USD"
pub_year:2011
pub_month:7
pub_day:19
stock_symbol:"NASDAQ:Z"
\_id:52cdef7c4bab8bd675297f15
name:"Nielsen"
ipo:Object
valuation_amount:1600000000
valuation_currency_code:"USD"
pub_year:2011
pub_month:1
pub_day:26
stock_symbol:"NYSE:NLSN"
\_id:52cdef7c4bab8bd675297de0
name:"Yelp"
ipo:Object
valuation_amount:1300000000
valuation_currency_code:"USD"
pub_year:2012
pub_month:3
pub_day:2
stock_symbol:"NYSE:YELP"
\_id:52cdef7d4bab8bd675299bd8
name:"Chegg"
ipo:Object
valuation_amount:1100000000
valuation_currency_code:"USD"
pub_year:2013
pub_month:11
pub_day:14
stock_symbol:"NYSE:CHGG"
\_id:52cdef7d4bab8bd67529984e
name:"Chegg"
ipo:Object
valuation_amount:1100000000
valuation_currency_code:"USD"
pub_year:2013
pub_month:11
pub_day:14
stock_symbol:"NYSE:CHGG"
\_id:52cdef7e4bab8bd67529a415
name:"RPX Corporation"
ipo:Object
valuation_amount:1096000000
valuation_currency_code:"USD"
pub_year:2011
pub_month:5
pub_day:4
stock_symbol:"RPXC"
\_id:52cdef7c4bab8bd675298649
name:"Higher One"
ipo:Object
valuation_amount:1060000000
valuation_currency_code:"USD"
pub_year:null
pub_month:null
pub_day:null
stock_symbol:"NYSE:ONE"

### 10. Retrieve the 10 companies with most employees, order by the `number of employees`

\_id:52cdef7d4bab8bd67529941a
name:"Siemens"
number_of_employees:405000
\_id:52cdef7c4bab8bd67529856a
name:"IBM"
number_of_employees:388000
\_id:52cdef7d4bab8bd675299d33
name:"Toyota"
number_of_employees:320000
\_id:52cdef7c4bab8bd675297e89
name:"PayPal"
number_of_employees:300000
\_id:52cdef7e4bab8bd67529b0fe
name:"Nippon Telegraph and Telephone Corporation"
number_of_employees:227000
\_id:52cdef7d4bab8bd675298aa4
name:"Samsung Electronics"
number_of_employees:221726
\_id:52cdef7d4bab8bd675298b99
name:"Accenture"
number_of_employees:205000
\_id:52cdef7e4bab8bd67529a657
name:"Tata Consultancy Services"
number_of_employees:200300
\_id:52cdef7e4bab8bd67529aa51
name:"Flextronics International"
number_of_employees:200000
\_id:52cdef7d4bab8bd675299156
name:"Safeway"
number_of_employees:186000
\_id:52cdef7c4bab8bd675297e6f
name:"Sony"
number_of_employees:180500
\_id:52cdef7c4bab8bd675298517
name:"LG"
number_of_employees:177000
\_id:52cdef7d4bab8bd675299d31
name:"Ford"
number_of_employees:171000
\_id:52cdef7d4bab8bd675298b28
name:"Boeing"
number_of_employees:160000
\_id:52cdef7e4bab8bd67529bb5c
name:"Digital Equipment Corporation"
number_of_employees:140000
\_id:52cdef7c4bab8bd675297fc2
name:"Nokia"
number_of_employees:125000
\_id:52cdef7d4bab8bd675299839
name:"MItsubishi Electric"
number_of_employees:107000
\_id:52cdef7d4bab8bd675299bc3
name:"MItsubishi Electric"
number_of_employees:107000
\_id:52cdef7d4bab8bd675298d67
name:"Bertelsmann"
number_of_employees:100000
\_id:52cdef7c4bab8bd6752987ad
name:"Comcast"
number_of_employees:100000

### 11. All the companies founded on the second semester of the year. Limit your search to 1000 companies.

{founded_day: {$gt: 90}}

### 12. All the companies founded before 2000 that have an acquisition amount of more than 10.000.000

{founded_year: {$lt:2000},  acquisition: {$gt: 10.000.000}}

### 13. All the companies that have been acquired after 2010, order by the acquisition amount, and retrieve only their `name` and `acquisition` field.

{acquisition: {$gt: 2010}}
{name: 1, acquisition: 1}

### 14. Order the companies by their `founded year`, retrieving only their `name` and `founded year`.

{founded_year: -1}
{founded_yea: 1, name: 1}

### 15. All the companies that have been founded on the first seven days of the month, including the seventh. Sort them by their `acquisition price` in a descending order. Limit the search to 10 documents.

<!-- Your Code Goes Here -->

### 16. All the companies on the 'web' `category` that have more than 4000 employees. Sort them by the amount of employees in ascending order.

{category_code: "web", number_of_employees: {$gt: 4000}}
{number_of_employees: 1}

### 17. All the companies whose acquisition amount is more than 10.000.000, and currency is 'EUR'.

{acquisition: {$gt: 10000000}}

### 18. All the companies that have been acquired on the first trimester of the year. Limit the search to 10 companies, and retrieve only their `name` and `acquisition` fields.

<!-- Your Code Goes Here -->

### 19. All the companies that have been founded between 2000 and 2010, but have not been acquired before 2011.

<!-- Your Code Goes Here -->
