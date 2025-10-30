# Array Manipulation Exercises

This project contains several exercises to practice array operations using Node.js and a JSON file with a list of products.

Each exercise includes an example of the expected result.

---

## 1️⃣ Filter all products with a price greater than 1000

**Example Result:**
```json
[
  {
    "id": 2,
    "name": "Product 2",
    "category": "Electronics",
    "price": 1200,
    "stock": 10,
    "origin": "Argentina"
  }
]
```

---

## 2️⃣ Get the names of all products from Argentina that cost less than 500

**Example Result:**
```json
["Product 3", "Product 4", "Product 5"]
```

---

## 3️⃣ Calculate the total stock value of all products (price × stock)

**Example Result:**
```
Total stock value: 139935.00
```

---

## 4️⃣ Get the average price of all products made in Germany

**Example Result:**
```
Average price (Germany): 492.70
```

---

## 5️⃣ Calculate the total stock value grouped by origin and category

**Example Result:**
```json
{
  "Germany": {
    "Furniture": 81395.5
  },
  "Argentina": {
    "Electronics": 12000,
    "Groceries": 15000
  }
}
```
