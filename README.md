# Product Table
## Date:08-07-2025
## Objective:

To create a structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes.

## Tasks:

### 1. Set Up the Basic HTML Structure:

Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the document layout.

Include a ```<title>``` such as "Product Table".

### 2. Create a Table Element:

Use the ```<table>``` tag to begin the product table.

### 3. Add a Table Header:

Use the ```<thead>``` section with a ```<tr>``` row and three ```<th>``` elements:

Product Name

Product Price

Description

### 4. Insert Table Body Rows:

Use the ```<tbody>``` section with multiple ```<tr>``` rows.

In each row, use three ```<td>``` cells for:

The name of the product (e.g., Laptop, Phone)

The price (e.g., ₹45,000, $499)

A short description (e.g., "High-speed performance", "Budget-friendly")

### 5. Ensure Semantic Structure:

Include ```<caption>``` if needed to describe the table purpose.

Use meaningful text inside the table for clarity.

### 6. No CSS or JavaScript:

Keep the table design strictly in HTML for simplicity.
## HTML Code:
```
<!DOCTYPE html>
<html>
<head>
    <title>Product Table</title>
    <style>
        body {
            background-color: rgb(187, 188, 189);
            font-family: 'Times New Roman', Times, serif;
        }
        table {
            margin: auto;
            border: 2px;
            border-collapse: collapse;
            width: 80%;
        }
        th {
            background-color: #83c1b7;
            color: white;
            padding: 10px;
            text-align: center;
        }
        td {
            border: 1px solid #83c1b7;
            padding: 10px;
        }
        tr:hover {
            background-color: #83c1b7;
        }
        tr:nth-child(even) {
            background-color: #83c1b7;
        }
        caption {
            margin-top: 20px;
            margin-bottom: 20px;
            font-size: 20px;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <h1>Product Table</h1>

    <table border="1">
        <thead>
            <tr>
                <th>Product Name</th>
                <th>Product Price</th>
                <th>Description</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Keyboard</td>
                <td>1,200</td>
                <td>Mechanical keys</td>
            </tr>
            <tr>
                <td>Monitor</td>
                <td>7,499</td>
                <td>Full HD display</td>
            </tr>
            <tr>
                <td>Printer</td>
                <td>6,299</td>
                <td>Wireless printing</td>
            </tr>
        </tbody>
    </table>

</body>
</html>


```
## Output:

![image](https://github.com/user-attachments/assets/80c0e9a7-5148-480c-848a-ee95cd00afc4)


## Result:
A structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes is created successfully.
