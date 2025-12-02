A complete online ordering system for a waffle and drinks shop, featuring a beautiful pink-themed UI with role-based access (Customer, Staff, Admin) and comprehensive order management.

📋 Overview
This is a fully functional web-based ordering system built with vanilla HTML, CSS, and JavaScript. The system allows customers to browse menu items, place orders with delivery options, while staff and administrators can manage orders and users.

🎨 Features
👥 User Roles
Customer: Browse menu, add to cart, place orders with delivery options, track orders

Staff: View and update order status, monitor deliveries

Admin: Full system control - manage users, menu items, view all orders

🛒 Customer Features
Browse 32+ menu items (waffles and drinks)

Add items to cart with quantity selection

Multiple delivery service options (Foodpanda, GrabFood, Lalamove, etc.)

Address selection from Mabini, Batangas locations

Multiple payment methods (COD, GCash, Credit Card)

Real-time order tracking with visual progress indicator

View order history with detailed status

👨‍🍳 Staff Features
View all customer orders

Update order status through workflow:

Pending → Confirmed → Preparing → Ready → On the Way → Delivered/Completed

Cancel or mark failed deliveries

👑 Admin Features
Add/edit/delete users with validation

Add new menu items with image uploads

Edit/delete existing menu items

View comprehensive order reports

Monitor all customer orders and statuses

📱 Technical Features
Responsive design with Shopee-style grid layout

Beautiful pink gradient theme

Toast notifications for user feedback

Local storage simulation (in-memory data persistence)

Image upload support for menu items

Form validation with real-time feedback

Social media integration links

🚀 Quick Start
Open the index.html file in any modern web browser

Login with your credentials:

Customer: Username: customer, Password: password123

Staff: Any username + any password (8+ chars with letters)

Admin: Any username + any password (8+ chars with letters)

🔑 Login Credentials
Role	Username	Password	Notes
Customer	customer	password123	Pre-registered customer
Staff	Any	Any (8+ chars with letters)	Automatically created on first login
Admin	Any	Any (8+ chars with letters)	Automatically created on first login
📍 Available Delivery Addresses
All barangays in Mabini, Batangas (34 locations)

Includes: Anilao I & II, Bagalangit, Bulacan, Calamias, Estrella, Gasang, Laurel, Ligaya, Mainaga, Mainit, Majuben, Malimatoc I & II, Nag-Iba, Pilahan, Poblacion, Pulang Lupa, Pulong Anahao, Pulong Balibaguhan, Pulong Niogan, Saguing, Sampaguita, San Francisco, San Jose, San Juan, San Teodoro, Santa Ana, Santa Mesa, Santo Niño, Sili, Solo, Talaga Proper, Talaga East

🚚 Delivery Services & Fees
Service	Fee
Foodpanda	₱50
GrabFood	₱45
Lalamove Food	₱40
Maxim Food Delivery	₱35
Angkas Food	₱30
Pickup / Store	Free
💳 Payment Methods
Cash on Delivery (COD) - Pay when order arrives

GCash - Digital payment with reference number

Credit Card - Secure card payment with transaction ID

📊 Order Status Workflow
Pending - Order received, awaiting confirmation

Confirmed / Accepted - Order confirmed by staff

Preparing / Cooking - Kitchen is preparing the order

Ready for Pickup - Order ready for pickup/delivery

Picked Up / On the Way - Out for delivery

Delivered - Order successfully delivered

Completed - Transaction complete

Cancelled - Order cancelled

Failed / Unsuccessful Delivery - Delivery attempt failed

🛠️ Admin Panel Functions
Manage Users
Add new users (Customer, Staff, Admin)

Set email, address, and password

Password validation (8+ chars with letters)

Delete existing users

Manage Menu
Add new menu items with name, price, and image

Edit existing menu items

Delete menu items

Image upload support

View Orders
Comprehensive order listing

Filter by customer, status, or date

View payment and delivery details

🌐 Social Media Integration
Facebook: https://facebook.com

Instagram: https://instagram.com

TikTok: https://tiktok.com

🏢 Store Information
Address: 456 Tasty Avenue, Waffle Town, WT 67890

Phone: +63 912 345 6789

Email: contact@waffleanddrinks.com

Hours: Open Every Day: 8:00 AM – 10:00 PM

🎯 Mission & Vision
Mission: Provide the best waffles and drinks experience to every customer, ensuring quality, freshness, and happiness in every bite.

Vision: Be the most loved local dessert brand, spreading joy and delight through waffles and drinks across the community.

🔧 Technical Details
File Structure
text
project/
├── index.html              # Main application file
├── logo waffle.png         # Main logo
├── [menu item images]      # 32+ menu item images
├── [social media icons]    # Facebook, Instagram, TikTok icons
Dependencies
Google Fonts: Poppins (300, 500, 700 weights)

Browser Compatibility: Chrome, Firefox, Safari, Edge (modern browsers)

Data Storage
In-memory storage: Data persists during browser session

Local Storage: Not implemented (simulated with JavaScript arrays)

Image Storage: Base64 encoding for uploaded images

📱 Mobile Responsiveness
Responsive grid layout for menu items

Collapsible cart on mobile

Touch-friendly buttons and forms

Adaptive font sizes

🔒 Security Notes
Demo Purpose Only: Not production-ready

No Database: All data stored in browser memory (clears on refresh)

No HTTPS: Local file operation only

Password Validation: Basic client-side validation only

🚨 Limitations
Data lost on page refresh (in-memory storage)

No server-side validation

No actual payment processing

No email notifications

No persistent user sessions

👤 Customer Registration
New customers can register with username, email, and address

Password must be 8+ characters with letters

Registration available only for customer role

Auto-login after registration

🎨 Design Features
Pink gradient color scheme

Smooth animations and transitions

Hover effects on interactive elements

Badges for order status and delivery services

Visual order tracking with icons

📞 Contact & Support
For demo issues or questions, contact: contact@waffleanddrinks.com

📝 Usage Instructions
For Customers:

Login or register new account

Browse menu and add items to cart

Select delivery address and service

Choose payment method

Place order and track status

For Staff:

Login with any credentials (8+ char password with letters)

View orders in orders table

Update status using dropdown menu

Monitor delivery progress

For Admins:

Login with any credentials (8+ char password with letters)

Manage users in "Manage Users" panel

Add/edit menu items in "Manage Menu" panel

View all orders in "Customer Orders" panel

