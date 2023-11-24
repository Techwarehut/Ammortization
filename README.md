# Ammortization
Loan calculator that can use extra payments to pay off in avalanche, snowball or custom order of all your debts
Takes an array of loans as an input
You will need t specify the minimum payment and other fields in the struct array
You will also need to specify the extra amount you can spare 
Algo will generate an ammortization table for all loans applying the extra payment to the first and then the next once the first is paid off

// Input variables
$amount_due = 10000; // Example loan amount of $10,000

$interest_rate = 0.05; // Example interest rate of 5%

$payment_frequency = 'monthly'; // Example payment frequency of monthly

$minimum_payment = 100; // Example minimum payment of $100

$extra_payment = 50; // Example extra payment of $50
