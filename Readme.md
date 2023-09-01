# Thread Shed

Thread Shed is a small sewing hobby shop, and as a cashier, your daily responsibilities include tallying sales, calculating total revenue, and keeping track of customer names. Unfortunately, Thread Shed uses an outdated register system, storing all transaction data in one large, unwieldy string called `daily_sales`. The task is to parse this string, clean it up, and organize the data into more accessible lists.

## Tasks

### 1. Inspect `daily_sales`

Take a moment to inspect the `daily_sales` string to understand how each transaction is stored and how data within each transaction is organized.

### 2. Replace `;,;` with a Comma `,`

To split `daily_sales` into individual transactions, replace all instances of `;,;` with a comma `,`. Save the result in a variable called `daily_sales_replaced`.

### 3. Split into Individual Transactions

Split `daily_sales_replaced` into a list of individual transactions. Each transaction should be a separate element in the list, and save it as `daily_transactions`.

### 4. Print `daily_transactions`

Print the `daily_transactions` list to see how it looks.

### 5. Initialize `daily_transactions_split`

Define an empty list called `daily_transactions_split` which will be used to store split transaction data.

### 6. Split Transaction Data

Iterate through `daily_transactions` and split each transaction string using the comma `,` as the delimiter. Append the resulting split strings (which are now lists) to the `daily_transactions_split` list.

### 7. Print `daily_transactions_split`

Print the `daily_transactions_split` list to check its contents.

### 8. Clean Up Whitespace

Initialize an empty list called `transactions_clean`. Iterate through `daily_transactions_split` and, for each transaction, iterate through the different data points, stripping off any whitespace. Add each cleaned-up transaction to the `transactions_clean` list.

### 9. Print `transactions_clean`

Print the `transactions_clean` list to ensure that there is no unnecessary whitespace.

### 10. Create Empty Lists

Create three empty lists: `customers`, `sales`, and `thread_sold`. These lists will be used to collect individual data points for each transaction.

### 11. Populate Lists

Iterate through `transactions_clean`. For each transaction, append the customer's name to the `customers` list, the sale amount to the `sales` list, and the threads sold to the `thread_sold` list.

### 12. Print Lists

Print the `customers`, `sales`, and `thread_sold` lists to verify their contents.

### 13. Calculate Total Sales

Define a variable called `total_sales` and set it to 0.

### 14. Sum Sales

Iterate through the `sales` list. For each sale amount, remove the dollar sign `$`, convert it to a float, and add it to `total_sales`.

### 15. Print `total_sales`

Print the `total_sales` variable to determine the total revenue for the day.

### 16. Count Thread Colors

Define a function called `color_count` that takes one argument, `color`. The function should iterate through `thread_sold_split` and count the number of times the item is equal to the `color` argument. Then, it should return this count.

### 17. Test `color_count`

Test your `color_count` function by running `color_count('white')`. It should return 28.

### 18. Define Color List

Define a list called `colors` that contains all the colored threads offered at Thread Shed: `['red', 'yellow', 'green', 'white', 'black', 'blue', 'purple']`.

### 19. Print Color Counts

Using the `.format()` method and the `color_count()` function, iterate through the `colors` list and print a sentence for each color, indicating how many threads of that color were sold today.

For example:
- "The number of red threads sold today: 5"

This will provide the count of each color sold in a user-friendly format.

Feel free to reach out if you have any questions or need further assistance with this project.
