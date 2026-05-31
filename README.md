# Griham – Find Your Perfect Stay 🏠

**Griham** simplifies your search for accommodation and essential services. From accomodation listings to food , Gym and laundry, everything is a call away — designed for students and professionals.


🌐 **Live Demo**: [https://griham.thevshub.in](https://griham.thevshub.in)
 
---

## 🖼 Preview

### Homepage
![Homepage](https://github.com/iamvishveshs/iamvishveshs.github.io/blob/main/assets/png/griham-homepage.png)

### Meal Listings Page
![Meal Listings](https://github.com/iamvishveshs/iamvishveshs.github.io/blob/main/assets/png/griham-services.png)

---

## ✨ Features

### 🏡 Effortless Room Finder
- Verified flats, PGs, and shared homes
- Smart filters: location, room type
- One-click call button for instant contact

### 👯 Roommate Matching System
- Filter profiles by gender, lifestyle, and habits
- Criteria: smoking, drinking, pets, food preferences, etc.

### 🍱 Homestyle Tiffin Delivery
- View local tiffin and mess providers with photos
- Cuisine types and service names displayed

### 🧺 Laundry & Housekeeping Services
- Contact laundry and cleaning providers near you
- Fast access via direct call buttons

### 🚨 Emergency & Utility Contacts
- Quick-dial access to essential services: Hospitals, Fire Stations etc.

### 📧 Gmail Email Integration (PHPMailer)
- Registration confirmation emails
- Password reset via secure Gmail SMTP using app password

### 💻 Frontend & UX
- Built with HTML5, CSS3, JavaScript, jQuery
- Responsive and mobile-friendly design

---

## 🛠️ Tech Stack

| Category   | Tools / Languages            |
|------------|------------------------------|
| Frontend   | HTML, CSS, JavaScript, jQuery|
| Backend    | PHP (Procedural)             |
| Database   | MySQL                        |
| Email      | PHPMailer + Gmail SMTP       |

---

## 🧩 Project Setup

### ✅ Requirements
- PHP 7.4 +
- MySQL
- Apache server (XAMPP/LAMP/WAMP recommended)
 
---

## ⚙️ Setup & Installation Guide

### Clone the Repository

```bash
git clone https://github.com/iamvishveshs/griham.git
cd griham
```
### Database Configuration

#### Config areas
change these files to run the website smoothly

`./database.php`
`./admin/database.php`
`./owner/database.php`
`./user/database.php`
`./libs/database.php`


| Key | value     | 
| :-------- | :------- | 
| `$servername` | `MySQL Hostname e.g. localhost` | 
| `$username` | `MySQL username e.g root` |
| `$password` | `MySQL password` |
| `$dbname` | `griham_project` |


### User Authentication

##### Demo Accounts for Local user


| Role | Email     | Password                |
| :-------- | :------- | :------------------------- |
| `Admin` | `admin@gmail.com` |  `Demo@1234`|
| `Owner` | `owner@gmail.com` |  `Demo@1234`|
| `user` | `user@gmail.com` |  `Demo@1234`|

##### Note:

To use the `griham.thevshub.in` register and use your account 



### SMTP setup
Also change the credentials in 
change these files to run the website smoothly

`./libs/accoun_verification_success.php`
`./libs/otp-resend.php`
`./libs/reset-password-otp.php`
`./libs/send_email_otp.php`
`./libs/send-support-response-email.php`

| Key | Value     | 
| :-------- | :------- |
| `$mail->Username` | `Your Email Address` | 
| `$mail->Password` | `generate app password from google account` |
| `$mail->setFrom('your_email', 'Griham')`| `Your Email Address`|

`go to gmail and generate app password here`
`https://myaccount.google.com/apppasswords` 
 

---

## 📜 License
This project is licensed under the **GNU General Public License v3.0**. See the [LICENSE](LICENSE) file for details., 
