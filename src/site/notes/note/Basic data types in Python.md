---
{"dg-publish":true,"permalink":"/note/basic-data-types-in-python/","tags":["note","programming"]}
---


# Basic data types in Python

In [[Python\|Python]], the datatype is determined by the value you assign to the variable.

## Containers

- several different built-in container types: **lists**, **dictionaries**, **sets**, and **tuples**.

### Lists

- Python's version of an array

- anything inside quotes, a series of characters

- single or double quotes

**Some string [[methods\|methods]]:**

- [[title()\|title()]]

- [[name.upper()\|name.upper()]]

- [[name.lower()\|name.lower()]]

### Using variables in strings

```python
first_name = "Emilio"
last_name = "Flores"
full_name = f"{first_name} {last_name}"
message = f"Hello, {full_name.title()}!"
print(message)
```

