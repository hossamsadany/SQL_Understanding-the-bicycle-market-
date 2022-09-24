# SQL_Understanding-the-bicycle-market-
You work for a chain of bicycle stores. Your new team leader comes from a different industry and wants your help learning about the bicycle market. Specifically, they need to understand better the brands and categories for sale at your stores.
![Bicycle](https://user-images.githubusercontent.com/97473553/192090697-8b2e1c2d-9664-4a26-bfd3-0f44d0994376.jpg)

## 💾 The data 

### You have access to the following tables:

#### products
- "product_id" - Product identifier.
- "product_name" - The name of the bicycle.
- "brand_id" - You can look up the brand's name in the "brands" table.
- "category_id" - You can look up the category's name in the "categories" table.
- "model_year" - The model year of the bicycle.
- "list_price" - The price of the bicycle.

#### brands
- "brand_id" - Matches the identifier in the "products" table.
- "brand_name" - One of the nine brands the store sells.

#### categories
- "category_id" - Matches the identifier in the "products" table.
- "category_name" - One of the seven product categories in the store.

#### stocks
- "store_id" - store identifier
- "product_id" - Matches the identifier in the "products" table
- "quantity" - the quantity of products in this store
