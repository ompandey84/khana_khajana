# Khana_Khajana

Khana Khajana is a modern and responsive web-based food ordering and QR menu system. Users can browse digital menus, place orders, and make payments securely online. This project provides a seamless dining experience with a user-friendly interface and mobile-ready design.

-----

## About the Project

Khana Khajana is a digital restaurant menu and ordering system designed to replicate real-life restaurant experiences in an online environment. It is ideal for restaurants, cafes, or food vendors who want to digitize their ordering process using a QR-based or browser-accessed system.

This project combines a beautiful, Bootstrap-based frontend with a PHP and MySQL backend using the XAMPP stack to simulate a complete food ordering workflow.

-----

## Features

  * **Responsive Design**: The website works seamlessly across all screen sizes, including desktops, tablets, and mobile devices.
  * **QR Menu System**: (If implemented) Allows customers to scan a QR code to instantly access the digital menu on their smartphones.
  * **Category-wise Menu Browse**: Organize and display food items by categories for easy navigation.
  * **Cart and Order Management**: Users can easily add items to their shopping cart, review their selections, and place orders.
  * **User Authentication**: A robust login and registration system for managing user accounts.
  * **Online Payment Ready UI**: Includes an interface designed for future integration with various online payment gateways, ensuring secure transactions.
  * **Navigation via Account Icon**: Features a clean and intuitive navbar with dedicated user account navigation logic.
  * **Built Using Clean UI Practices**: Emphasizes a user-friendly and aesthetically pleasing interface design.

-----

## Technologies Used

This project is built using a combination of frontend and backend technologies to deliver a complete solution:

  * **Frontend**:
      * HTML5
      * CSS3
      * Bootstrap 5
      * JavaScript
  * **Backend**:
      * PHP
      * MySQL
  * **Local Development Environment**:
      * XAMPP (for Apache, MySQL, and PHP support)
  * **Other Tools**:
      * Git & GitHub (for version control)
      * Bootstrap Icons or Font Awesome (for iconography)
      * Google Fonts (for typography)

-----

## Getting Started

To get a local copy of Khana Khajana up and running on your system, follow these steps.

### Prerequisites

Make sure you have the following software installed on your computer:

  * A modern web browser (e.g., Chrome, Firefox, Edge)
  * **XAMPP**: Download and install XAMPP from the [official Apache Friends website](https://www.apachefriends.org/download.html).
  * **Git** (optional, but recommended for cloning the repository): Download from [git-scm.com](https://git-scm.com/downloads).

### Installation

1.  **Clone the repository**:

    ```bash
    git clone https://github.com/ompandey84/khana_khajana.git
    ```

2.  **Move the project into your XAMPP htdocs directory**:
    Copy the `khana_khajana` folder into your XAMPP's `htdocs` directory.

      * **Windows**: `C:\xampp\htdocs\`
      * **macOS**: `/Applications/XAMPP/htdocs/`
      * **Linux**: `/opt/lampp/htdocs/`

    Example command (replace `/path-to-xampp/` with your actual XAMPP installation path):

    ```bash
    cp -r khana_khajana /path-to-xampp/htdocs/
    ```

3.  **Start Apache and MySQL**:
    Open the XAMPP Control Panel and click the "Start" buttons for both Apache and MySQL.

4.  **Import the SQL database**:

      * Open your web browser and go to `http://localhost/phpmyadmin`.
      * Click on "New" in the left sidebar to create a new database. Enter a name (e.g., `khana_khajana`) and click "Create".
      * Select the newly created database from the left sidebar.
      * Go to the "Import" tab, click "Choose File", and select the `.sql` file provided in your repository (if available) to import your database schema and initial data.

5.  **Configure Database Connection (if needed)**:
    Ensure your PHP connection files (e.g., `config.php` or `db_connect.php`) are correctly configured to connect to your MySQL database (typically `username: root`, `password: <empty>`, `database_name: khana_khajana`).

-----

## Usage

Once you have completed the installation steps:

1.  **Run the application**: Open your web browser and visit `http://localhost/khana_khajana`.
2.  **The Home Page (`index.html`)** will load first, serving as the main entry point to the system.
3.  **Login/Register**: Click the user/account icon in the navbar to navigate to the Login Page. New users can proceed to the Registration Page from there.
4.  **Browse and Order**: After logging in, users can browse categorized menus, add desired items to their cart, and place orders.
5.  **Payment UI**: The integrated payment option UI is available for future payment gateway integrations.

-----

## Screenshots

You can upload and embed screenshots here for better visual representation of your project:

```
screenshots/
├── home.png
├── menu.png
└── login.png
```

To embed them in your `README.md`, use the following markdown:

-----

## Contributing

Contributions are highly welcome\! If you have suggestions for improvements or new features, please follow these steps:

1.  Fork the project.
2.  Create your feature branch: `git checkout -b feature/AmazingFeature`
3.  Commit your changes: `git commit -m 'Add some AmazingFeature'`
4.  Push to the branch: `git push origin feature/AmazingFeature`
5.  Open a Pull Request.

If you like this project, don’t forget to give it a star\!

-----

## Contact

**Om Pandey**

  * **Email**: ompandey8435@gmail.com
  * **GitHub**: [ompandey84](https://www.google.com/search?q=https://github.com/ompandey84)
  * **LinkedIn**: [pandeyom](https://www.google.com/search?q=https://www.linkedin.com/in/pandeyom)

**Project Repository**: [https://github.com/ompandey84/khana\_khajana](https://github.com/ompandey84/khana_khajana)

-----
