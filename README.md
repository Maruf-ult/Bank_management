
# 🏦 Bank Management System

## 📌 Description  
**Bank Management System** is a Django-based web application designed for **secure and streamlined financial operations**. Users can authenticate, deposit funds, withdraw money, and request loans. Admins oversee and process loan approvals, ensuring reliable decision-making. With **cookie-based sessions**, user profile management, and **Gmail-powered email notifications**, the system prioritizes transparency, privacy, and real-time communication.
## Live Link
## https://bank-management-1-20sh.onrender.com

## ✨ Features  
- 💰 Deposit and withdraw funds securely  
- 🧾 Request loans with admin review and approval  
- 🧑‍💼 Admin panel for processing loan requests and managing transactions  
- 🙍‍♂️ User profile editing and information updates  
- 📧 Email notifications sent via Gmail after every financial transaction  
- 🔐 Authentication with cookie-based session management  

## 🛠️ Technologies Used  
- **Python & Django** – Web framework and backend logic  
- **PostgreSQL** – Lightweight database for development  
- **HTML / CSS / Bootstrap** – Clean and responsive frontend  
- **JavaScript** – Interactive components  
- **Gmail SMTP** – Email integration  
- **Django Admin Panel** – Administrative dashboard  

## ⚙️ Installation  

1. **Clone the repository**

   git clone https://github.com/Maruf-ult/Bank_Management_System

2. Open the terminal in the project directory:
    ```
     cd Blog-App
    ```

3. Create and activate a virtual environment:
   ```
     python -m venv env
   ```
      Activate the virtual environment:
      On Linux/Mac:
   ```
     source env/bin/activate
   ```
   
      On Windows:
   ```
     env\Scripts\activate
   ```


5. Install dependencies:
    ```
       pip install -r requirements.txt
    ```

6. Configure the database:

- Create a `.env` file or configure your database settings in `settings.py`
- Run the following migrations:

  ```
    python manage.py makemigrations
    python manage.py migrate
  ```

6. Create a superuser for admin access:
   ```
     python manage.py createsuperuser

   ```

7. Start the development server:
    ```
        python manage.py runserver
    
    ```
