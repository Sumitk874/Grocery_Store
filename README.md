# Grocery Store Application
![image](https://github.com/user-attachments/assets/d5b63569-f70f-4c27-a88f-5f89c0902bbf)
![image](https://github.com/user-attachments/assets/d12656a3-e7eb-4b3d-a657-63181015a478)
![image](https://github.com/user-attachments/assets/57dd17fa-dba4-479e-ab34-0e42674fe770)
![image](https://github.com/user-attachments/assets/6268e385-4b53-41ce-b3cf-efe964b2f6eb)


## Overview

This project is a uses three-tier architecture and is built using the following technologies:

- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Backend**: Python, Flask
- **Database**: MySQL

The application provides functionality to add new orders and manage products, including adding and removing products.

## Features

- Add new orders
- Add new products
- Remove existing products

## Project Structure

```
project-root/
├── backend/
│   ├── __init__.py
│   ├── orders_dao.py
│   ├── products_dao.py
│   ├── uom_dao.py
├── ui/
│   ├── css/
│   │   ├── bootstrap.min.css
│   │   ├── custom.css
│   │   ├── sidebar-menu.css
│   │   ├── style.css
│   ├── js/
│   │   ├── custom/
│   │   │   ├── common.js
│   │   │   ├── dashboard.js
│   │   │   ├── manage-product.js
│   │   │   ├── order.js
│   │   ├── packages/
│   │       ├── bootstrap.min.js
│   │       ├── jquery.min.js
│   ├── index.html
│   ├── manage-product.html
│   ├── order.html
├── server.py
├── sql_connection.py
└── README.md
```

## Prerequisites

- Python 3.x
- MySQL
- Flask
- Git

## Installation

1. **Clone the repository**:
   ```sh
   git clone https://github.com/username/repo.git
   cd repo
   ```

2. **Configure the database**:
   - Create a MySQL database.
   - Update the `sql_connection.py` file with your database connection details.

3. **Run the application**:
   ```sh
   python backend/server.py
   ```

## Usage

### Adding a New Product

1. Navigate to the **Manage Product** page.
2. Fill in the product details.
3. Click on the **Add Product** button.

### Removing a Product

1. Navigate to the **Manage Product** page.
2. Select the product to remove.
3. Click on the **Remove Product** button.

### Adding a New Order

1. Navigate to the **Order** page.
2. Fill in the order details.
3. Click on the **Add Order** button.

## Contributing

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Commit your changes.
5. Push to the branch.
6. Create a pull request.

## License

This project is licensed under the MIT License.

## Acknowledgements

- [Flask](https://flask.palletsprojects.com/)
- [Bootstrap](https://getbootstrap.com/)
- [MySQL](https://www.mysql.com/)

---

Feel free to customize this README to better fit your project and any additional details you'd like to include.
