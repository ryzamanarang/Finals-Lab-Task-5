# [Finals Lab Task 5 - Views, Stored Procedures and Functions](https://github.com/user-attachments/files/20127326/Finals.Lab.Task.5.-.Manarang.docx)
- This portfolio demonstrates the use of SQL views, stored procedures, and stored functions to manage and manipulate database data. It covers tasks such as filtering data with views, updating records with stored procedures, and retrieving data using functions.

## Step-by-Step Process:
1. **Setup MySQL Workbench:**

   * Open XAMPP and start the MySQL server.
   * Connect MySQL Workbench to the server.
   * Execute practice queries using the `democodes.sql` file.

2. **Use Inventory Database:**

   * Open the `inventory.sql` file to begin the tasks.

3. **Create Views:**

   * Create a view to display vendor information and products with in-date from 2002 onward.
   * Create a view for products with prices between 100-150.
   * Create a view to compute the total price for products sold by specific vendors.

4. **Create Stored Procedure:**

   * Create a stored procedure that updates the vendor name from 'Bryson, Inc.' to 'Bryson and Co'.

5. **Create Function:**

   * Create a function that takes vendor code and state as parameters to display product details.

6. **Execute and Document:**

   * Execute the SQL statements and capture screenshots of the commands and outputs.

# Screenshots of Codes and Outputs:
### 1. CREATE A VIEW that will display the vendors_code, vendors name, product
description p_indate, of all products with p_indate from 2002 onwards
- ![Image](https://github.com/user-attachments/assets/249275e6-d2f6-4f09-b510-6cd08c9313bd)

## Output
- ![Image](https://github.com/user-attachments/assets/0bb8bb1d-c472-45c5-9f99-58cefd54edd1)

### 2. CREATE a VIEW that will display all products whose price range is between 100-150
- ![Image](https://github.com/user-attachments/assets/52cc906f-2bee-40ef-8984-bc95d9fc41a2)

## Output
- ![Image](https://github.com/user-attachments/assets/bddffe46-fd96-445f-bd0e-f393656c5f76)

### 3. Create a VIEW that will COMPUTE for the (TOTAL_PRICE) of ALL
PRODUCTS by getting the (P_ONHAND x P_PRICE) Sold by vendors with
the following v_code (21344, 23119 and 24288)
- ![Image](https://github.com/user-attachments/assets/f16c765d-414b-46cf-8126-596e0ac697aa)
## Output
- ![Image](https://github.com/user-attachments/assets/e4fdd94d-f0e6-4a46-b8d8-d0b599b28af5)

### 4. CREATE a STORED PROCEDURE that WILL take a SINGLE PARAMETER and
UPDATED the Name of Vendor ‘Bryson,Inc.’ to ‘Bryson and Co’.
- ![Image](https://github.com/user-attachments/assets/1b56e89a-7816-42f7-8b93-00cc7a8ac21f)
## Output
- ![Image](https://github.com/user-attachments/assets/9327d62a-d0de-4937-abb5-a986e7eaed9d)

### 5. CREATE A Function that will take 2 parameters(v_code and
v_state) and display All the product description and price based on
the parameters passed to the function
- ![Image](https://github.com/user-attachments/assets/8d450dce-b097-43db-b18f-4b1d4b9ebc5e)
## Output
- ![Image](https://github.com/user-attachments/assets/4f949477-bdff-4e72-9a5e-0daef59af771)
