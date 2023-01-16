# Django 4 - Online Shop

### Building an Online Shop
- Creating an online shop project
- Creating product catalog models
- Registering catalog models on the administration site
- Building catalog views
- Creating catalog templates

### Building a shopping cart
- Using Django sessions
    
        For better performance use a cache-based session engine. Django supports Memcached out of the box and you can find third-party cache backends for Redis and other cache systems.

- Storing shopping carts in sessions
- Creating shopping cart views
  - Adding items to the cart
  - Adding products to the cart
- Creating a context processor for the current cart

### Registering customer orders
- Creating order models
- Including order models in the administration site
- Creating customer orders

### Managing Payments and Orders
- Integrating a payment gateway
  - Creating a Stripe account
  - Building the payment process
  - Exporting orders to CSV files
    - Adding custom actions to the administration site
  - Extending the administration site with custom views