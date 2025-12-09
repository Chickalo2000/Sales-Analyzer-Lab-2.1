import csv

def calculate_total_sales(filename):

# This function reads a CSV file and calculates the total sales.

# It assumes the CSV has 'product_name', 'price', 'quantity' columns.

total = 0.0

with open(filename, mode='r') as file:

csv_reader = csv.DictReader(file)

for row in csv_reader:

price = float(row['price'])

quantity = int(row['quantity'])

total += price * quantity

return total

if __name__ == "__main__":

sales_data_file = 'sales_data.csv'

total_sales = calculate_total_sales(sales_data_file)

print(f"Total sales from {sales_data_file}: ${total_sales:.2f}")
