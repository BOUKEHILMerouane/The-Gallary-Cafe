# 🍽️ **The Gallary Cafe - Full-Stack Web Application**

A comprehensive full-stack web application developed for **The Gallary Cafe**, designed to streamline restaurant operations. The platform includes a variety of features catering to customers, employees,s and administrators, with a strong focus on security, performance, and user experience.

## **Technologies Used**
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Package Management**: Composer

---

## **Key Features**

### **Customer Features**
- **Cart Management**: Add, remove, and manage items in the cart.
- **User Authentication**:
  - Account creation (Sign up)
  - Login and Logout
  - Password reset functionality
  - OTP for secure authentication
  - User verification
- **Reservations**: Book and manage table reservations.
- **User Profile**: Edit and update personal information.

### **Admin Features**
- **User Management**:
  - Create and manage customer, admin, and staff accounts.
  - Manage user roles and permissions.
- **Menu Management**:
  - Add, update, or delete menu items.
  - Categorize menu items for better organization.
- **Order Management**: Oversee both online and in-store orders.
- **Reservations Management**: Monitor and manage customer table reservations.
- **Restaurant Management**:
  - Manage tables and seating arrangements.
  - View detailed order and reservation histories.

### **Employee Features**
- **Menu Management**: Update and maintain the restaurant menu.
- **Order Management**: Monitor and fulfill both online and in-house orders.
- **Reservations Management**: Handle customer reservation requests.
- **Restaurant Management**: Maintain tables and seating arrangements.
- **View Information**: Access detailed order and reservation data.

### **Customer Features**
- **Ordering**: Place, modify, and track online orders.
- **Reservations**: Make and manage restaurant bookings.
- **Menu Browsing**: View the available menu with item descriptions and prices.

---

## **Utility & Security Features**

- **Access Control**: Role-based access control, restricting certain actions and pages to authorized users.
- **Cross-Site Request Forgery (CSRF) Protection**: Enhanced security for forms to prevent unauthorized requests.
- **HTTPS Enforcement**: All traffic is automatically redirected to HTTPS to ensure secure communication.
- **Security Headers**:
  - `X-Content-Type-Options: nosniff`: Prevents browsers from incorrectly interpreting file types.
  - `X-Frame-Options: DENY`: Prevents the page from being embedded in an iframe.
- **Session Security**:
  - Secure session handling with HTTP-only cookies and encrypted data transmission over HTTPS.
  - Sessions are regenerated every 30 minutes to mitigate session fixation risks.
  - Session validation for IP address and user agent consistency to prevent session hijacking.
  - Automatic session termination if inconsistent session data is detected.
- **CSRF Tokens**: All forms are secured with CSRF tokens to prevent unauthorized form submissions.
- **Secure Logout**: Ensures proper session termination and logout procedures.
- **Error Handling**: Comprehensive error management for smoother user experience.
- **SSL Certificate**: Ensures secure, encrypted connections across the application.

---

## **Installation & Setup**

1. Clone the repository:

   ```bash
   git clone https://github.com/KevinThulnith/Restaurant-Website.git


# PHPMailer Integration

## 1. Install PHPMailer

To integrate email functionality, you need to install PHPMailer via Composer. Run the following command in your project directory:

```bash
composer require phpmailer/phpmailer


## 1. Autoload PHPMailer

To use PHPMailer in your project, you must load its dependencies by including the following lines in your PHP code:

```php
use PHPMailer\PHPMailer\PHPMailer;
use PHPMailer\PHPMailer\Exception;

require '../vendor/autoload.php';

# View Installed SSL Certificates

To manage and view SSL certificates installed on your local server,  you can use the following command::

```bash
certmgr.msc

