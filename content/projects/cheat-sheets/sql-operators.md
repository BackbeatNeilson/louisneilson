---
title: "SQL Operators Cheatsheet"
# weight: 1
# hero: images/guide/sigmund-4MoIpDcSlr4-unsplash.jpg
---
# SQL Operators Cheatsheet

Content adapted from [W3Schools](https://www.w3schools.com/sql/sql_operators.asp). 

# SQL Operators Cheatsheet

## Comparison Operators

| Operator | Description | Logic Symbol |
|----------|-------------|--------------|
| `=` | Equal to | = |
| `>` | Greater than | > |
| `<` | Less than | < |
| `>=` | Greater than or equal to | ≥ |
| `<=` | Less than or equal to | ≤ |
| `<>` | Not equal to | ≠ |

## Bitwise Operators

| Operator | Description | Logic Symbol |
|----------|-------------|--------------|
| `&` | Bitwise AND | ⋅ |
| `\|` | Bitwise OR; inclusive disjunction | ∨ |
| `^` | Bitwise exclusive OR; exclusive disjunction | &nLeftrightarrow; or ⊕|

## Logical Operators

| Operator | Description | Logic Symbol |
|----------|-------------|--------------|
| `ALL` | TRUE if all subquery values meet the condition | ∀ |
| `AND` | TRUE if all conditions are TRUE | ⋅ |
| `ANY` | TRUE if any subquery value meets the condition | ∃ |
| `BETWEEN` | TRUE if operand is within a range | |
| `EXISTS` | TRUE if subquery returns one or more records | ∃ |
| `IN` | TRUE if operand equals one of a list of values | |
| `LIKE` | TRUE if operand matches a pattern | |
| `NOT` | TRUE if condition(s) is NOT TRUE | ~ |
| `OR` | TRUE if any condition is TRUE | ∨ |
| `SOME` | TRUE if any subquery value meets the condition | ∃ |

## Arithmetic Operators

| Operator | Description |
|----------|-------------|
| `+` | Add |
| `-` | Subtract |
| `*` | Multiply |
| `/` | Divide |
| `%` | Modulo |

## Compound Operators

| Operator | Description | Usage |
|----------|-------------|-------|
| `+=` | Shorthand for `x = x + 5` | Adds a value to a variable and assigns the result back to the variable. Used to increment a value in place. |
| `-=` | Shorthand for `x = x - 3` | Subtracts a value from a variable and assigns the result back. Used to decrement a value. |
| `*=` | Shorthand for `x = x * 2` | Multiplies a variable by a value and assigns the result back. Used to scale values. |
| `/=` | Shorthand for `x = x / 4` | Divides a variable by a value and assigns the result back. Used to reduce values proportionally. |
| `%=` | Shorthand for `x = x % 10` | Gets the remainder when dividing and assigns it back. Used for cyclic operations like wrapping numbers. |
| `&=` | Shorthand for `x = x & 0xFF` | Used to clear specific bits or extract bit patterns from binary data. |
| `^=` | Shorthand for `x = x ^ 0x01` | Used to toggle or flip specific bits. |
| `\|*=` | Shorthand for `x = x \| 0x80` | Used to set specific bits to 1 while preserving others. |