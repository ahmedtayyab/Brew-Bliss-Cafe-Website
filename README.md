# Brew Bliss Cafe Website

## Project Overview
Brew Bliss Cafe is a full-featured café website that combines elegant design with robust functionality. The project features a dynamic menu system, user authentication, shopping cart functionality, and a comprehensive admin panel for business management.

## Key Features

### Frontend
- Modern, responsive design that works seamlessly across all devices
- Intuitive user interface with smooth navigation
- Dynamic menu display with filtering and search capabilities
- Interactive shopping cart with real-time updates
- Contact form with validation and feedback

### Backend
- Secure user authentication system
- Role-based access control
- Database-driven content management
- Real-time cart functionality with GST calculation
- Session management and security features

### Admin Panel
- Secure admin authentication with password hashing
- Comprehensive dashboard for business monitoring
- Menu management system:
  - Add, edit, and delete menu items
  - Update prices and images
  - Manage categories and special offers
- User management:
  - View and manage user accounts
  - Upgrade/downgrade user roles
  - Monitor user activity
- Message center:
  - Read and respond to customer inquiries
  - Track message history
  - Export communication data

### SEO & Performance
- Professional SEO implementation
- XML sitemap generation
- Robots.txt configuration
- Meta tags optimization
- Mobile-friendly design
- Fast loading times
- Proper URL structure

## Technical Stack
- **Frontend:** HTML5, CSS3, JavaScript
- **Backend:** PHP
- **Database:** MySQL
- **Version Control:** Git
- **Hosting:** AWS EC2

## Installation

1. **Clone the repository**
   ```bash
   git clone [repository-url]
   ```

2. **Database Setup**
   - Import the provided SQL files:
     - `create_database.sql`
     - `create_admin_table.sql`
     - Other necessary SQL files

3. **Configuration**
   - Update `config.php` with your database credentials
   - Configure your web server settings
   - Set up proper file permissions

4. **Admin Access**
   - Default admin credentials:
     - Username: `admin`
     - Password: `admin123`
   - Change default credentials immediately after first login

## Security Features
- Password hashing
- SQL injection prevention
- XSS protection
- CSRF protection
- Secure session management
- Input validation and sanitization

## File Structure
- `/admin` - Admin panel files
- `/member` - User-specific files
- `/Images` - Media assets
- Root directory - Main application files

## Contributing
1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Support
For support, please use the contact form on the website or create an issue in the repository.

CODED BY AHMAD TAYYAB

## Acknowledgments
- All images and content are for educational/demo purposes only.
