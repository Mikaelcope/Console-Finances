# Console-Finances
Creating JavaScript for calculations to solve questions relating to finance.

## Discription
I have created a JavaScript file that allows a user to check specific financial information from a range of information provided.

### Installation
Click on the following link to access the URL:
https://mikaelcope.github.io/Console-Finances/


### Usage
Once the URL has loaded this is what you will see: 
![alt text](./Images/Screenshot%202.png)
The navigational buttons will direct you through the page.
The previous work display has link buttons to the webpages.
There are hyperlinks and a drop down to get in touch.

### Credits
EdX front end web developement course. <br>
https://www.goodreads.com/quotes/tag/connection-with-people#:~:text=%E2%80%9CConnecting%20with%20others%20gives%20us%20a%20sense%20of,which%20empowers%20our%20humanity.%E2%80%9D%20%E2%80%95%20Susan%20C.%20Young <br>
Boostrap. <br>
Font Awesome. <br>
Visme. <br>
Quote by Susan C. Young, GoodReads.

### License
MIT License

Copyright (c) [2023] [Mikael Cope]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.






//Correct//



// var greatestincrease=0
// var increase=0
// var currentprofit=finances[i][1]
// var previousprofit=finances[i-1][1]

// for(var i=1;i<finances.length;i++){
//   var increase = currentprofit - previousprofit

//   if currentprofit >= previousprofit{}
// }


// initalize vars for 
// totalMonths,
//  netChangeProfits = 0, 
// averageChangeInProfits, 
// var greatestProfit = ['date', 0] can be reassigned  to something like  ['feb-2012', 123234] in order to remember both the month and profit
// var greatestLoss = ['date', 0]
// to get total change between months
// loop through the finances array starting at index 1, instead of 0, 
// current month = finances[i][0]
// current revenue = finances[i][1]
// calculate change between the current month and previous month's revenue: var difference = finances[i][1] - finances[i -1][1]
//check if difference if greater than greatestProfit, if so reassign 
// sum the difference onto the netChangeProfits variable: netChange = netChange + difference
// once the loop completes we have looked at every month and calculated the total netChangeProfits so now we can get the average by simply dividing by the length - 1
// netChangeProfits / finances.length - 1 (edited) 