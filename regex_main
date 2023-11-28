import re

text = (" Product date is  09-11-2023"
        " Product id is Turtle#001 ")

date_pattern = "\d{2}-\d{2}-\d{4}"
product_pattern = "[A-Za-z]+#\d{3}"

date = re.findall(date_pattern, text)
product_id = re.findall(product_pattern, text)

print(date)
print(product_id)
