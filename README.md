
# 🚗 Car Rental System 

This is a backend-driven Car Rental System developed using **PHP**, **MySQL**, **HTML**, **CSS**, and **JavaScript**. It enables users to register, log in, view available cars, and book rentals based on flexible durations (hourly, daily, weekly, monthly). The project includes basic client-side interactivity and form validations using JavaScript.

---

## 💡 Features
- ✅ User Registration & Login
- ✅ Car Listings with Details
- ✅ Book Cars by Duration (hour/day/week/month)
- ✅ Admin Panel for Car Management (optional)
- ✅ JavaScript for Form Validation
- ✅ Responsive Design with HTML & CSS
- ✅ MySQL Database Integration

---

## 🧰 Tech Stack
- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: PHP  
- **Database**: MySQL  

---

## 📁 Project Structure
```
carrental/
├── db.php              # Database connection
├── register.php        # User registration
├── login.php           # User login
├── list_cars.php       # Display available cars
├── car_details.php     # Car information page
├── book_car.php        # Booking logic
├── script.js           # JavaScript validation
├── style.css           # CSS styling
└── (optional SQL file)
```

---

## 🚀 How to Run the Project (Locally)

1. **Clone the Repository**
   ```bash
   git clone https://github.com/eshwarbattuwar/Car-Rental-Backend.git
   cd Car-Rental-Backend
   ```

2. **Set Up MySQL Database**
   - Open [phpMyAdmin](http://localhost/phpmyadmin)
   - Create a new database named: `car_rental`
   - Import the provided `car_rental.sql` file (if available)

3. **Configure Database Connection**
   - Open `db.php` and ensure it looks like this:
   ```php
   $conn = mysqli_connect("localhost", "root", "", "car_rental");
   ```
   - Adjust username/password if needed (default is usually `root` with no password)

4. **Deploy on XAMPP**
   - Move the project folder to `C:\xampp\htdocs\`
   - Start **Apache** and **MySQL** from XAMPP Control Panel
   - Open your browser and go to:  
     👉 `http://localhost/carrental`

5. **Use the Application**
   - Register a new user via `register.php`
   - Log in via `login.php`
   - Browse and book cars from `list_cars.php`
   - Admin functionalities can be added in separate files if required

---

## 👨‍💻 Developer

**Battuwar Eshwar**  
GitHub: [https://github.com/eshwarbattuwar](https://github.com/eshwarbattuwar)  
Email: eshwarbattuwar@gmail.com

---

## 📄 License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT). Feel free to use, modify, and share.
