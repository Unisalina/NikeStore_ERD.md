# NikeStore_ERD.md

erDiagram
Product 
Inventory ||--|{ Product:Stock replenishment
Inventory 
Sales ||--|{ Customer:Transaction
Sales 
Customer ||--0{ Product:Order
Customer 