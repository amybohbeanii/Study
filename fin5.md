 ## discounted cash flow valuation
 
  ## learning goals
  1) Determine future and present value of investments with multiple cash flows
  2) Calculate loan payments and find interest rate on loan
  3) describe how loans are amortized or paid off
  4) explain how interest rates are quoted 
  
  * in reality, most investments have multiple cash flows  (calc car payments, student loan payments..)
  * this section is about valuing multiple cash flows
  
  ```
  examples for calculating future and present value of a series of cash flows
  ```
  
   ## valuing level cash flows: annuities and perpetuities
   * multiple cash flows that are equal payments. (car loans, home mortgages..)
   
   * annuity is a series of constant cash flows that occur at end of each period for fixed number of periods
   
   ```
   formula to find annnuity, C, given t and r
   
   Annuity present value = C * (1-present value factor)/r
   = C * (1-(1/(1+r)^t / r)
   
   to do on calculator:
   3 N
   10 I/Y
   500 PMT
   CLR FV
   CPT PV
   
   or
   5 N
   18 I/Y
   100000 PV
   CLR FV
   CMPT PMT
   
   or to find number of payments
   1.5 I/Y
   -20 PMT
   1000 PV
   CLR FV
   CPT N
   
   or to find the rate
   4 N
   1000 PMT
   -3000 PV 
   CLR FV
   CPT I/Y
   
   or to find annuity future values
   30 N
   8 I/Y
   -2000 PMT
   CLR PV
   CPT FV
   
   ```
   
    ## annuity due is like a leasing an apartment. First lease payment is due immediately. second payment is due at beginnign of second month. Annuity due is annuity for which cash flows occur at the beginning of each period. 
   ```
    annuity due value = ordinary annuity value * (1+r)
    ```
    
    ## perpetuity = special case of annuity when level stream of cash flows continues forever.
    ```
    perpetuity PV = C/r
    ex: investment offers perpetual cash flows of $500 every yr. Return you require on such investment is 8%. What is value of investment?
    $6,250 = $500/.08
    ```
    
     * preferred stock is important ex of perpetuity. Buyer is promised fixed cash dividend every period forever.
     
      ## comparing rates/effect of compounding periods
      * interest rates are quoted many diff ways. sometimes rates are quoted in deliberately deceptive ways to mislead borrowers and investors.
      * if there is different compounding during the year, then theres concern about what the rate really is
      * for example 5 percent every six months is not the same as 10% per year
      
     ## calc and compare effective annual rates (EAR)
     ```
     EAR = (1+Quoted rate/m)^m - 1
     
     ex: suppose you were offered 12 percent compounded monthly
     EAR = (1+.12/12)^12 - 1
     = 12.6825%
     
     ex2: you can also find quoted rate
     ```
     
      ## APR = annual percentage rate 
      ```
      example of rate you actually pay
      a typical credit card agreement quotes interest rate of 18% APR. Monthly payments required. Whats the actual interest rate you pay on such a credit carD?
      EAR = (1+.18/12)^12-1
      = 19.56%
      ```
      
      ## loan types and loan amortization
       * three basic types of loan repayment
       * pure discount and interest-only loans, the principal is repaid all at once
       1) pure discount loans
       2) interest-only loans
       3) amortized loans
       
       ## pure discount loans
       * simplest form of loan to calculate. Borrower receives money today and repays single lump sum at some time in the future
      
      ```
      suppose a borrower was able to repay 25,000 in five years. If were the lender and we wanted 12% interest rate on the loan, how much are we willing to lend?
      present value = $25,000/1.12^5
      =$14,186
      
      ex2: t bills is a promise by gov to repay a fixed amount at some time in future. If t-bill promises to repay 10k in 12 months, market interest rate ie 7%, how much will bill sell for in the market?
      present value = 1k/1.07
      = $9345.79
      ```
      
       ## interest-only loans
       * repayment plan that calls for  borrower to pay interest each period and repay entire principal at some point in future
       * corp bonds have the general form of an interest-only loan
       
       ## amortized loans
        * lender may require te borrower to repay parts of the loan amount over time.
        * process of paying off loan by making regular principal reductions is called amortizing the loan
        * almost all consumer loans (car loans, mortages) work this way.
        
        ```
        amortization schedule
        ```
        
