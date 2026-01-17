# LCBO Casamigos Store Site

This project is a static website showcasing Casamigos tequila products available at a specific LCBO store. The site was built using product and store data sourced from the LCBO Postgres database and is designed to present store information, a producer flyer, product promotions, and a WordPress database overview.

---

## Project Overview

The website highlights Casamigos as a featured producer and displays three of its products:
- Casamigos Blanco
- Casamigos Reposado
- Casamigos Añejo

Product identifiers and attributes were obtained by querying the LCBO database, including LCBO product numbers, pricing, alcohol content, and store inventory data. Product images were added through external web research.

---

## Pages Included

### Home (`index.html`)
Landing page that provides navigation to all sections of the site.

### Store Page (`store.html`)
Contains detailed information for a specific LCBO location, including:
- Store address
- Operating hours
- General store information

### Producer Page (`producer.html`)
A web flyer highlighting Casamigos as the selected producer, featuring:
- Three products
- Bottle images
- Key product details

### Posts Page (`posts.html`)
Includes three promotional-style posts, each focusing on one Casamigos product and using data sourced from the LCBO database.

### WordPress Database Page (`wordpress.html`)
Provides an overview of the WordPress database schema, listing the main tables and explaining the purpose of each.

---

## Data Source

Product and store data were retrieved from the LCBO Postgres database, including:
- `products`
- `producers`
- `stores`
- `inventories`

SQL queries were used to identify product IDs, match LCBO product numbers, and determine store availability.

---

## Technologies Used

- HTML5
- CSS3
- PostgreSQL (LCBO dataset)
- Docker
- GitHub

---

## Assets

All images are stored locally in the `assets/` directory and are used for educational purposes.

---

## Author

Richard Lu  
GitHub: https://github.com/richardyjlu-byte
