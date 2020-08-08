# angular-6-registration-login-example

Angular 6 User Registration and Login Example with Webpack 4

[Angular youtube](https://www.youtube.com/watch?v=WWQZCDegWHg)

# Design
1. Build an application - eChihuo supporting Mobile, Web
2. Frondend - Angular
3. Backend - Python, Django
4. Database - MongoDB, SQlite
5. Deployment - cloud AWS (Dev, Production)

# Modules
1. Login page                               Jun
2. Shopping                                 Qianjiang
3. Shopping Cart
4. Payment
5. Shippment
6. Database connection                      Qianjiang
7. Logging 
8. Admin -- User role, acccount managment   Hao

# Data model
    Entities
        Vender
           ID
            Frist Name
            Last Name
            Phone
            Address 
        Customer
            ID
            Frist Name
            Last Name
            Phone
            Address
        
        Category
            ID
            Name
            List<Product>
        
        Product
            ID
            CateloryID
            Name
            UnitPrice

    Order
        ID
        OrderTime
        CustomerID
        Shipping Type
        Shipping Address
        Shipping Time
        Suggestion
        Status (PreOrder, Confirmed, OutOfDoor, Paid, Delivered, Cannelled, Returned, Refunded)
        Command

    OrderDetail
        ID
        OrderID
        List<Product>
        Quantity
        TotalPrice

