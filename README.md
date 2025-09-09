# JWT Authentication System  

This is a **JWT-based authentication system** built for learning purposes. It includes user authentication and account management features with a **React frontend** and a **Node.js + Express.js backend**. The system uses **Mailtrap** for email delivery (verification, password reset, etc.).  

---

## 🚀 Features  

- **User Signup** – Create a new account with email & password.  
- **User Login** – Authenticate with JWT tokens.  
- **Email Verification** – Users receive a verification email after signup.  
- **Forgot Password** – Request a password reset link via email.  
- **Reset Password** – Securely reset password using a token.  
- **JWT Authentication** – Access-protected routes with JWT.  
- **Mailtrap Integration** – Used for testing email sending in development.  

---

## 🛠️ Tech Stack  

### Frontend  
- **React.js**  
- **Axios** (for API calls)  
- **React Router** (for navigation)  

### Backend  
- **Node.js**  
- **Express.js**  
- **JWT (jsonwebtoken)**  
- **Bcrypt.js** (for password hashing)  
- **Nodemailer** (for sending emails via Mailtrap)  

### Database  
- **MongoDB**

---

## 📩 Email Sending (Mailtrap)  

This project uses **Mailtrap** to send emails for:  
- Account verification  
- Forgot password link  

👉 You need to create a [Mailtrap account](https://mailtrap.io/), get your SMTP credentials, and configure them in your `.env` file.  

---


