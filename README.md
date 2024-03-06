# Account-Class
This Python program defines an Account class with attributes for balance and account number. The class provides methods for debit, credit, and printing the account balance.

## Features

### Attributes:
* balance: Represents the current balance of the account.
* account_no: Represents the account number.

### Methods:
* print_balance(): Prints the total balance of the account.
* debit(amount): Deducts the specified amount from the account balance.
* credit(amount): Adds the specified amount to the account balance.
* update_balance(): Prints the total balance after any debit or credit operation.

## Usage
1. Creating an Account Instance:

        acc1 = Account(initial_balance, account_number)

2. Printing Balance:

       acc1.print_balance()

3. Debit Operation:

        acc1.debit(amount)

4. Credit Operation:

        acc1.credit(amount)

5. Updating Balance:

        acc1.update_balance()


## Example

    # Create an Account instance
    acc1 = Account(10000, 1234567890)
    
    # Print initial balance
    acc1.print_balance()
    
    # Perform debit and credit operations
    acc1.debit(500)
    acc1.credit(20000)
    
    # Update and print the balance
    acc1.update_balance()
    
    # Continue with more operations...


I hope this helps! Feel free to pull requests and use the code. 
