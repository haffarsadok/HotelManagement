# 🏨 Hotel Management System - Bluebird Hotel

A comprehensive web-based hotel management system built with PHP and MySQL, featuring user authentication, room booking, and administrative controls.

## 🌟 Features

### User Features
- **User Registration & Login**: Secure account creation and authentication
- **Room Booking System**: Interactive booking interface with detailed reservation forms
- **Room Selection**: Multiple room types available (Superior, Deluxe, Guest House, Single Room)
- **Booking Management**: Date selection, meal preferences, and bedding options
- **User Dashboard**: Personal booking management interface

### Staff Features
- **Staff Login Portal**: Separate authentication system for hotel staff
- **Administrative Panel**: Complete booking management and oversight
- **Reservation Management**: View, confirm, and manage customer bookings

### Room Types Available
- **Superior Room** - Premium accommodation with full amenities
- **Deluxe Room** - Luxury accommodation with enhanced services
- **Guest House** - Comfortable mid-range accommodation
- **Single Room** - Budget-friendly single occupancy rooms

## 🛠️ Technology Stack

- **Backend**: PHP 7.4+
- **Database**: MySQL
- **Frontend**: HTML5, CSS3, JavaScript
- **Framework**: Bootstrap 5.0.2
- **Icons**: Font Awesome 6.2.0
- **Alerts**: SweetAlert
- **Animations**: AOS (Animate On Scroll)

## 📁 Project Structure

```
HotelManagement/
├── admin/                 # Administrative panel files
├── css/                   # Stylesheets
├── image/                 # Images and media files
├── javascript/            # Client-side scripts
├── index.php             # Login/Registration page
├── home.php              # Main user dashboard
├── config.php            # Database configuration
├── logout.php            # Session logout handler
├── bluebirdhotel.sql     # Database schema
└── README.md             # Project documentation
```

## 🚀 Installation & Setup

### Prerequisites
- XAMPP/WAMP/LAMP server
- PHP 7.4 or higher
- MySQL 5.7 or higher
- Web browser

### Installation Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/haffarsadok/HotelManagement.git
   cd HotelManagement
   ```

2. **Setup Database**
   - Start your MySQL server
   - Create a new database named `bluebirdhotel`
   - Import the provided SQL file:
   ```sql
   mysql -u root -p bluebirdhotel < bluebirdhotel.sql
   ```

3. **Configure Database Connection**
   - Open `config.php`
   - Update database credentials if needed:
   ```php
   $server = "localhost";
   $username = "root";
   $password = "";
   $database = "bluebirdhotel";
   ```

4. **Deploy to Web Server**
   - Copy project files to your web server directory
   - For XAMPP: `htdocs/HotelManagement/`
   - For WAMP: `www/HotelManagement/`

5. **Access the Application**
   - Open your web browser
   - Navigate to: `http://localhost/HotelManagement/`

## 💻 Usage

### For Customers
1. **Registration**: Create a new account using the signup form
2. **Login**: Access your account with email and password
3. **Browse Rooms**: View available room types and amenities
4. **Make Reservation**: Fill out the booking form with:
   - Personal information
   - Room preferences
   - Check-in/Check-out dates
   - Meal options
5. **Confirmation**: Receive booking confirmation

### For Staff
1. **Staff Login**: Use staff credentials to access admin panel
2. **Manage Bookings**: View and process customer reservations
3. **Update Status**: Confirm or modify booking status
4. **Customer Management**: Handle customer inquiries and requests

## 🎨 Features Showcase

### Hotel Amenities
- 🏊‍♂️ Swimming Pool
- 🧘‍♀️ Spa Services
- 🍽️ 24/7 Restaurant
- 💪 24/7 Gymnasium
- 🚁 Helicopter Service
- 📶 Free WiFi

### Booking Options
- **Bedding Types**: Single, Double, Triple, Quad
- **Meal Plans**: Room Only, Breakfast, Half Board, Full Board
- **Room Capacity**: Flexible occupancy options
- **International Support**: Multiple country selection

## 🔒 Security Features

- Password encryption and validation
- Session management for user authentication
- SQL injection protection
- Form validation and sanitization
- Secure logout functionality

## 📱 Responsive Design

The application features a fully responsive design that works seamlessly across:
- Desktop computers
- Tablets
- Mobile devices
- Various screen resolutions

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Developer

**Created by @haffar** - [GitHub Profile](https://github.com/haffarsadok)

## 📞 Support

For support and inquiries:
- 📧 Email: [Contact via GitHub](https://github.com/haffarsadok)
- 📱 Social Media: Follow project updates
- 🐛 Issues: [Report bugs here](https://github.com/haffarsadok/HotelManagement/issues)

## 🔮 Future Enhancements

- Payment gateway integration
- Email notification system
- Advanced reporting dashboard
- Mobile application
- Multi-language support
- Room availability calendar
- Customer review system

---

⭐ **Star this repository if you found it helpful!**


