# The-E-Market-Shop
E-Market Project Using Spring Boot, JPA, Thymeleaf, and MySQL


### E-Market Project Using Spring Boot, JPA, Thymeleaf, and MySQL

#### **Project Overview**
The E-Market project is an online shopping platform designed to facilitate the buying and selling of products. It is built using the Spring Boot framework, which provides a robust and scalable backend. The project employs JPA (Java Persistence API) for data access and management, Thymeleaf as the template engine for the presentation layer, and MySQL as the relational database for storing data.

#### **Key Features**

1. **User Authentication and Authorization:**
   - **User Registration and Login:** Secure user registration and login functionalities using Spring Security, with role-based access control (e.g., Admin, Seller, Buyer).
   - **Password Encryption:** Passwords are securely stored using hashing techniques.

2. **Product Management:**
   - **Product Listing:** Sellers can add, update, and delete products. They can also manage product inventory and pricing.
   - **Product Categories:** Products are categorized for easy navigation and filtering.
   - **Product Search and Filter:** Buyers can search for products using keywords and filters based on categories, price range, and ratings.

3. **Shopping Cart and Checkout:**
   - **Shopping Cart:** Buyers can add products to the shopping cart, update quantities, and remove items.
   - **Checkout Process:** Secure checkout process with order summary, payment integration, and order confirmation.

4. **Order Management:**
   - **Order Tracking:** Buyers can track the status of their orders.
   - **Order History:** Buyers can view their past orders and transaction details.

5. **Admin Dashboard:**
   - **User Management:** Admins can manage user accounts, including creating, updating, and deleting user profiles.
   - **Product Management:** Admins can oversee product listings and make changes as necessary.
   - **Order Management:** Admins can manage and monitor all orders, update order statuses, and handle refunds or returns.

#### **Technologies and Tools Used**

- **Backend:**
  - **Spring Boot:** Provides a streamlined and efficient way to build Java-based applications.
  - **Spring Data JPA:** Used for data persistence and CRUD operations with the MySQL database.
  - **Spring Security:** Ensures secure access control and authentication.

- **Frontend:**
  - **Thymeleaf:** A modern server-side Java template engine for rendering HTML views.

- **Database:**
  - **MySQL:** A relational database management system used to store user, product, and order data.

- **Others:**
  - **Maven:** Used for project build and dependency management.
  - **JPA/Hibernate:** For ORM (Object-Relational Mapping) with MySQL.
  - **RESTful APIs:** For communication between the frontend and backend.

#### **Architecture**
The project follows a layered architecture, including the following layers:
- **Presentation Layer:** Handles the user interface and interactions, implemented with Thymeleaf templates.
- **Service Layer:** Contains business logic and handles interactions between the presentation and data layers.
- **Data Access Layer:** Manages data persistence and retrieval using JPA and MySQL.
- **Database Layer:** MySQL database for data storage.
  
![image](https://github.com/user-attachments/assets/6174cadf-9a7e-4da9-a088-0c356cf7ff91)

![image](https://github.com/user-attachments/assets/d02de50d-2575-4eb9-be81-f90afe367f09)

![image](https://github.com/user-attachments/assets/f88ad426-4370-4a79-b7b0-1c36568766e2)

![screencapture-localhost-8080-2024-08-14-12_54_23](https://github.com/user-attachments/assets/52cceeeb-9891-48da-ab69-47733e124e48)

![screencapture-localhost-8080-products-2024-08-14-12_57_55](https://github.com/user-attachments/assets/67770f7d-5437-4c30-a741-5494f5ed154b)

![image](https://github.com/user-attachments/assets/dc9c1ded-9266-490f-8784-ab2f4077cfbf)

![image](https://github.com/user-attachments/assets/80b9cdc8-c68d-4678-80b9-35eb268a1ba9)

![image](https://github.com/user-attachments/assets/00af269a-a44d-4540-b00f-33901ef4436e)

#### **Future Enhancements**
- **Integration with Payment Gateways:** To provide secure online payment options.
- **Advanced Search and Recommendation:** Implementing features like product recommendations and advanced search filters.
- **Mobile-Friendly Design:** Enhancing the user interface to be responsive and mobile-friendly.

This E-Market project provides a comprehensive platform for online shopping, making it convenient for both buyers and sellers to engage in e-commerce activities.
