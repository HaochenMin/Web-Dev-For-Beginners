# Data Types Practice

## Instructions

Imagine you are building a shopping cart. Write some documentation on the data types that you would need to complete your shopping experience. How did you arrive at your choices?

# String
Names of the products are strings as a readable format for customers to identify what the products are.

# BigInt
Order IDs can be stored as BigInt it may exceed the safe range for Number over time.

# Number
Product numbers, quantities, and prices are of Number type for simplicity and compatibility, and won't exceed the safe range.

# Boolean
Booleans can be used to indicate whether an item is in stock or not.

# Null
When removing or resetting a field or value such as a shipping address or payment information, it should be set to null.

# Undefined
When a product is being added to the cart without its price being fetched, it should be initially set as undefined.

## Rubric

Criteria | Exemplary | Adequate | Needs Improvement
--- | --- | --- | -- |
||The six data types are listed and explored in detail, documenting their use|Four datatypes are explored|Two data types are explored|
