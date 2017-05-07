 ## intro to valuation: time value of money
 ## learning objectives
 1) determine future value of investment made today
 2) determine present value of cash to be received at future date
 3) calc return on investment
 4) predict how long it takes for investment to reach desired value
 5) evaluate trade off between dollars today and dollars at some future time
 
  * time value of money = dollar in hand today is worth more than a dollar promised at some time in the future
  
  ## future value and compounding
  * future value (FV) is amount of money an investment grows to over some period of time at some given interest rate
  ```
  so for single period of $100 that pays 10% interest per year, how much do you have in 1 year?
  $110 is the future of $100 invested for 1 year at 10%. $100 today is worth $110 in 1 year. Principal * (1+r)
  ```
  
  * compounding is the process of leaving money and any accumulated interest in an investment for more than one period, thereby reinvesting the interest
  * compounding the interest means earning interest on the interest = compound interest
  * simple interest = is the interest not reinvested, so interest is earned each period only on the original principal
  * simple interest is constant every year, but compound interest earned gets bigger every year
  * doublign the interest rate more than doubled the future value...
  
  ```
  so for more than one period...
  the general equation to find future value of $1 invested for t period at a rate of r per period is:
  Future value = $1 * (1+r)^t
  ```
  
   * compound interest example
   
  ```
  investment pays 12%. You invest $400.
  1) How much will you have in 3 years? 7 yrs?
  2) At end of 7 yrs, how much interest have you earned? How much is from compounding?
  
  future value factor is (1+r)^t = 1.12^3 = 1.4049
  $400*1.4049 = $561.97 for three yrs
  $400*1.12^7 = $884.27 for seven yrs
  
  interest is $844.27-$400 = $484.27. Simple interest is $400*.12 = $48 simple interest every yr. 7*$48=$336 in simple interest for 7 ears. 
  $484.27-$336 = $148.27 from compounding
  ```
  
  ```
  to calculate with financial calc
  -100 PV
  10 I/Y
  5 N
  CPT FV
  ```
  
   ## Present value and discounting
   
   * questions relating to: Suppose you need $10k in 10 yrs and you earn 6.5%. How much to invest today to reach my goal?
   * instead of compounding money forward into future, we discount it back to the present
   
   ```
   PV = $1 * [(1/1+r)^t]
   or 
   PV = $1 / (1+r)^t
   
   example: Suppose you need $1000 in 2 years. If you can earn 7% how much do you have to invest
   PV = $1000/1.14 = $873.44
   
   example2: Suppose you need $1000 in 3 years. If you can earn 15% how much do you have to invest today?
   PV = $1000 * [(1/(1+.15)^3] = $657.50
   $657.50 is the present or discounted value of $1000 to be received in 3 years at 15%
   ```
   
    * discount rate is the rate in brackets
    * discounted cash flow (DCF) valuation is the PV of a future cash flow to determine its worth today
    * PV factor is just reciprocal of FV factor ...
    
    ```
    future value factor = (1+r)^t
    present value factor = 1/(1+r)^t
    
    ## determining discount rate/rate of return/return
     * four parts to equation, PV, FV, discount rate (r), life of investment (t)
     ```
     PV = FV/(1+r)^t
   ```
   
    * just substitute and use financial calculator
    
    ```
    Ex1: finding r 
    Suppose investment costs $100 and doubles in 8 yrs
    $100 = $200/(1+r)^8
    200/100 = (1+r)^8
    2^(1/8) 
    r = 9%
    
    Ex2: finding r
    Suppose future value is 2million present value is 1k, 200 yrs
    1000=2million/(1+r)^200
    2000 = (1+r)^200
    r = 3.87%
    
    calc: 200 n, -1000PV, 2000000FV, CPT I/Y
    ```
    
    
  
