price = []
n = int(input("Enter number of products: "))
# Insertion
for i in range(n):
    p = int(input("Enter price: "))
    price.append(p)
# Traversal
print("Product Prices:", price)
# Deletion
d = int(input("Enter price to delete: "))
if d in price:
    price.remove(d)
    print("Price deleted")
else:
    print("Price not found")
print("Updated Prices:", price)# Product-price-management-
Practical programs
