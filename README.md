# Brew Bliss Cafe Website

A modern, responsive website for Brew Bliss Cafe featuring a complete menu, user authentication, and interactive features.

![Brew Bliss Cafe](Images/Logo.png)

## 👥 Team Division

### Student 1: Frontend Development & UI/UX
**Responsibilities:**
- Design and implement responsive layouts
- Create and maintain CSS styles
- Implement interactive features
- Develop user interface components
- Ensure cross-browser compatibility
- Optimize images and assets
- Implement animations and transitions

**Key Files:**
- `style.css`
- `index.php` (frontend part)
- `menu.php` (frontend part)
- `about.php` (frontend part)
- All image assets and icons

### Student 2: Backend Development & Database
**Responsibilities:**
- Database design and implementation
- User authentication system
- Session management
- Database queries and optimization
- Security implementation
- API development
- Error handling

**Key Files:**
- `db_connect.php`
- `create_database.sql`
- `login.php`
- `register.php`
- Database-related components

### Student 3: Integration & Additional Features
**Responsibilities:**
- Connect frontend and backend components
- Implement shopping cart functionality
- Develop contact form with Nodemailer
- Create admin dashboard
- Implement order management system
- Add analytics and tracking
- Testing and debugging

**Key Files:**
- `cart.php` (future)
- `contact.php` (future)
- `admin/` directory (future)
- Integration scripts
- Testing documentation

## 🌟 Features

### Current Features
- **Responsive Design**: Fully responsive layout that works on all devices
- **User Authentication**
  - User registration with email validation
  - Secure login system with password hashing
  - Session management
  - User profile display in navbar
- **Menu System**
  - Categorized menu items (Hot Coffee, Cold Coffee, Specialty Drinks, Tea Selection, Pastries & Snacks)
  - Detailed item descriptions and pricing
  - High-quality images for all items
  - Add to cart functionality (UI ready)
- **About Us Page**
  - Company story and mission
  - Team member profiles
  - Values and commitments
  - Coffee sourcing information
- **Interactive Elements**
  - Modal confirmations for actions
  - Hover effects on menu items
  - Smooth transitions and animations

### Work Division for Team Members

#### Student 1 (Frontend Developer)
**Current Tasks:**
- Complete responsive design implementation
- Enhance UI animations and transitions
- Optimize image loading and performance
- Implement remaining frontend components

**Future Tasks:**
- Design and implement admin panel UI
- Create order management interface
- Develop analytics dashboard layout
- Implement advanced animations for better UX

#### Student 2 (Backend Developer)
**Current Tasks:**
- Complete user authentication system
- Implement database security measures
- Set up API endpoints
- Optimize database queries

**Future Tasks:**
- Develop admin panel backend
- Implement order processing system
- Create analytics tracking system
- Set up automated email notifications

#### Student 3 (Integration Specialist)
**Current Tasks:**
- Connect frontend and backend components
- Implement basic cart functionality
- Set up contact form backend
- Create testing documentation

**Future Tasks:**
- Implement full shopping cart system
- Develop order tracking system
- Create user dashboard
- Implement payment gateway integration

### Future Updates and Enhancements

#### User Account Features
- **Enhanced Shopping Cart**
  - Persistent cart using local storage
  - Save cart items for logged-in users
  - Multiple cart management
  - Cart sharing functionality
  - Wishlist feature

#### Admin Panel Development
- **Dashboard Features**
  - Real-time sales analytics
  - Inventory management
  - User management system
  - Order tracking and management
  - Menu item management
  - Promotional campaign tools

#### Additional Features
- **Payment Integration**
  - Multiple payment gateway support
  - Secure payment processing
  - Order confirmation system
  - Invoice generation

- **Advanced User Features**
  - Loyalty program
  - Points system
  - Personalized recommendations
  - Order history and reordering
  - Customizable user preferences

- **Mobile App Development**
  - Native mobile application
  - Push notifications
  - Mobile ordering system
  - Location-based services

- **Analytics and Reporting**
  - Sales reports
  - Customer behavior analysis
  - Inventory tracking
  - Performance metrics

## 🛠️ Technologies Used

- **Frontend**
  - HTML5
  - CSS3
  - JavaScript
  - PHP
- **Backend**
  - PHP
  - MySQL
- **Database**
  - MySQL
- **Version Control**
  - Git

## 📋 Prerequisites

- XAMPP (or similar local server environment)
- PHP 7.4 or higher
- MySQL 5.7 or higher
- Web browser (Chrome, Firefox, Safari, Edge)

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Brew-bliss-Cafe-Static-Website.git
   ```

2. **Set up XAMPP**
   - Install XAMPP if not already installed
   - Start Apache and MySQL services
   - Place the project in the `htdocs` folder

3. **Database Setup**
   - Open phpMyAdmin (http://localhost/phpmyadmin)
   - Create a new database named `brew_bliss_db`
   - Import the `create_database.sql` file

4. **Configuration**
   - Navigate to `db_connect.php`
   - Update database credentials if needed:
     ```php
     $host = 'localhost';
     $dbname = 'brew_bliss_db';
     $username = 'your_username';
     $password = 'your_password';
     ```

5. **Start the Application**
   - Open your web browser
   - Navigate to `http://localhost/Brew-bliss-Cafe-Static-Website`

## 📁 Project Structure

```
Brew-bliss-Cafe-Static-Website/
├── Images/                  # All website images
├── about.php               # About us page
├── index.php              # Home page
├── menu.php              # Menu page
├── login.php            # User login
├── register.php        # User registration
├── navbar.php         # Navigation component
├── footer.php        # Footer component
├── db_connect.php   # Database connection
├── style.css       # Main stylesheet
└── README.md      # Project documentation
```

## 🔐 User Authentication

The website implements a secure authentication system:

1. **Registration**
   - Email validation
   - Password hashing
   - Duplicate email check
   - Success/error feedback

2. **Login**
   - Secure password verification
   - Session management
   - Remember me functionality (planned)
   - Password reset (planned)

## 🛍️ Menu System

The menu is organized into categories:
- Hot Coffee
- Cold Coffee
- Specialty Drinks
- Tea Selection
- Pastries & Snacks

Each item includes:
- High-quality image
- Description
- Price
- Add to cart button

## 📧 Contact Form (Future Implementation)


## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Authors

- Your Name - Initial work

## 🙏 Acknowledgments

- All images used are property of Brew Bliss Cafe
- Icons from [Icon Source]
- Inspiration from [Inspiration Source]

## 📞 Support

For support, email support@brewblisscafe.com or create an issue in the repository.

---

Made with ❤️ by [Your Name] 