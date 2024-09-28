# NikeStore_ERD.md

erDiagram
Product {
Quantity
Product type
Product ID
}
Inventory ||--|{ Product:"Stock replenishment"
Inventory {
Product ID
Product type
Product quantity
}
Sales ||--|{ Customer:"Transaction"
Sales {
Customer ID
Product Type
Product Quantity
Product Price
Transactions Record
}
Customer ||--0{ Product:"Order"
Customer {
Customer ID
First name
Last Name
Phone Number
}