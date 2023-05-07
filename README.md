Download Link: https://assignmentchef.com/product/solved-itse2321-program-9-class-called-savingsaccount
<br>
Create a class called <strong>SavingsAccount</strong>.  The class should have a static variable named, <strong>annualInterestRate</strong>, to store the annual interest rate for all account holders.  Each object of the class should contain a private instance variable named, <strong>savingsBalance</strong>, indicating the amount the saver currently has on deposit.

Write methods to perform the following:

<ul>

 <li>calculateMonthlyInterest – calculates the monthly interest by multiplying the <strong>savingsBalance</strong> by <strong>annualInterestRate </strong>divided by 12. This interest should be added to the balance.</li>

 <li>depositAmount – allows the customer to deposit money into the account (thereby increasing the balance. Do not accept negative amount.</li>

 <li>withdrawAmount – allows the customer to withdraw money from the account (thereby decreasing the balance. Do not accept negative amount.</li>

 <li>modifyInterestRate (static) – allows the bank to change the annual interest rate. Accept only floating-point values between 2 and 5.</li>

 <li>toString – get string representation of <strong>SavingsAccount</strong> object (prints the variable, savingsBalance</li>

</ul>

Write a test class named <strong>TestSvingsAccount</strong> to test the <strong>SavingsAccount</strong> class.  Instantiate two objects, saver1 and saver2, with balances of $2000.00 and $3000.00, respectively.  Set the annual interest rate to 4%, then calculate the monthly interest for each of the 12 months and print the new balance, at the end of each month, for both savers.

Deposit $1500.00 to saver1’s account and withdraw $550.00 from saver2’s account. Next change the annual interest rate to 5%, calculate the next month’s interest and print the new balance for both savers.