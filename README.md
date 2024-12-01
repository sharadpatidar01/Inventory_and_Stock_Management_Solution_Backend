# 🛒 Inventory Management System for Shop Owners

This project is an **Inventory and Stock Management System** designed for small shop owners. It helps them efficiently manage their product inventory, monitor stock levels, and handle daily operations like adding, updating, and deleting products. It also features secure authentication, image storage, and email notifications for better user experience.

## 🌐 Live Demo

View the live demo here: [Inventory and Stock Management System - Live Demo](https://smartstockmanager.vercel.app/)

## 📊 Flowchart Overview

Below is a flowchart representing the architecture of the system:

![Flowchart](https://github.com/sharadpatidar01/Inventory_and_Stock_Management_Solution_Frontend/blob/main/flowchart.png)  
*This flowchart depicts the API interaction and user operations involved in managing products and profiles.*


## 📷 Screenshots

Below are some screenshots from the **Inventory and Stock Management System** following the user journey:

1.  **Home Page**  
   ![Home Page](https://github.com/sharadpatidar01/Inventory_and_Stock_Management_Solution_Frontend/blob/main/Home.png)
2.  **Register Page**  
   ![Register Page](https://github.com/sharadpatidar01/Inventory_and_Stock_Management_Solution_Frontend/blob/main/Register.png)

3. **Login Page**  
   ![Login Page](https://github.com/sharadpatidar01/Inventory_and_Stock_Management_Solution_Frontend/blob/main/Login.png)

4. **Forgot Password**  
   ![Forgot Password](https://github.com/sharadpatidar01/Inventory_and_Stock_Management_Solution_Frontend/blob/main/Forgot_Password.png)

5. **Dashboard**  
   ![Dashboard](https://github.com/sharadpatidar01/Inventory_and_Stock_Management_Solution_Frontend/blob/main/Dashboard.png)

6. **Add Product**  
   ![Add Product](https://github.com/sharadpatidar01/Inventory_and_Stock_Management_Solution_Frontend/blob/main/Add_Product.png)

7. **Product Search**  
   ![Product Search](https://github.com/sharadpatidar01/Inventory_and_Stock_Management_Solution_Frontend/blob/main/Product_Search.png)

8. **Product View**  
   ![Product View](https://github.com/sharadpatidar01/Inventory_and_Stock_Management_Solution_Frontend/blob/main/Product_View.png)

9. **Profile View**  
   ![Profile View](https://github.com/sharadpatidar01/Inventory_and_Stock_Management_Solution_Frontend/blob/main/Profile.png)

10. **Edit Profile**  
   ![Edit Profile](https://github.com/sharadpatidar01/Inventory_and_Stock_Management_Solution_Frontend/blob/main/Edit_profile.png)

11. **Change Password**  
   ![Change Password](https://github.com/sharadpatidar01/Inventory_and_Stock_Management_Solution_Frontend/blob/main/ChangePassoword.png)

12. **Report Bug**  
   ![Report Bug](https://github.com/sharadpatidar01/Inventory_and_Stock_Management_Solution_Frontend/blob/main/Report_Bug.png)
   

## 🛠️ Technologies Used

- **React**: For building the front-end user interface.
- **Node.js & Express**: For handling the back-end APIs.
- **MongoDB**: Database to store product and user data.
- **Cloudinary**: For storing product images.
- **JWT (JSON Web Token)**: For user authentication and authorization.
- **Nodemailer**: For sending email notifications (e.g., password resets, order updates).
- **Redux Toolkit**: For state management in the front-end.
- **Multer**: For handling file uploads in Node.js.

## 📥 Installation

To run this project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/inventory-management-system.git
   cd inventory-management-system
   ```

2. **Install dependencies for both client and server:**

   ```bash
   npm install
   cd client
   npm install
   ```

3. **Set up your environment variables:**

   - Create a `.env` file in the root directory.
   - Add the following keys:

     ```env
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     CLOUDINARY_API_KEY=your_cloudinary_api_key
     CLOUDINARY_API_SECRET=your_cloudinary_api_secret
     CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
     EMAIL_USER=your_email_service_username
     EMAIL_PASS=your_email_service_password
     ```

4. **Run the app:**

   ```bash
   npm run dev
   ```

   Open your browser and navigate to `http://localhost:3000` to view the app.

## 📝 Features

- **Product CRUD Operations**: Add, update, view, and delete products with associated images.
- **Secure Authentication**: Register and log in using JWT-based authentication.
- **Profile Management**: Update user profiles and manage password resets.
- **Image Upload**: Upload and manage product images using Cloudinary.
- **Responsive Design**: The application is mobile-friendly and works seamlessly across all devices.
- **Email Notifications**: Users receive emails for order confirmations, password resets, and other important actions.

## 📧 Contact

For any questions or feedback, feel free to reach out:

- **Email**: [patidarsharad01@gmail.com](mailto:patidarsharad01@gmail.com)
- **LinkedIn**: [Sharad Patidar](https://www.linkedin.com/in/sharadpatidar/)

## 💻 Developer

This project is developed and maintained by **Sharad Patidar**. I am passionate about creating digital solutions that help businesses optimize their operations.

Thank you for checking out this project! I hope it proves useful for managing your inventory. 😊✨

