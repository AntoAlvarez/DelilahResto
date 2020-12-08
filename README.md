# Delilah-Restó:

Back-end REST API project for Acámica

# Description:

Manages an online food delivery system for a restaurant. As ADMIN you can add products to the store, update or delete them. You can also take orders from users and update their status. As a registered USER you can log in, update your information or delete your account. You can get a list or available products, add them to the cart and procede to make an order.

# Version:

1.0.0

# Main file:

#### index.js

---

# Server:

Protocol = **http**
Hostname = **127.0.0.1 //localhost**
Port = **3000**

# NPM dependencies:

**NPM dependencies** declared in package.json file that must be installed to run the system:
**"bcrypt": **$ npm install bcrypt**
"body-parser": **$ npm install body-parser**
"compression":** $ npm install compression**
"dotenv": ** $ npm install dotenv**
"express": **$ npm install express**
"express-jwt":** $ npm install express-jwt**
"express-rate-limit":** $ npm install --save express-rate-limit**
"express-validator": **$ npm install express-validator**
"helmet": **$ npm install helmet --save**
"jsonwebtoken": **$ npm install jsonwebtoken**
"mysql2": **$ npm install --save mysql2**
"sequelize":** $ npm install sequelize\*\*

# Database connection:

Download XAMPP software from https://www.apachefriends.org/es/index.html
Import the **delilah.sql** file into http://localhost/phpmyadmin/

**Local configuration file (default)**
Host = **localhost**
Database name = **delilah**
Username = **root**
Port = **3306**

Access **connection.js** if you need to configure your local connection.

# Start the REST API:

$ npm run dev

# API documentation:

To see the API documentation import **spec.yaml** file into https://editor.swagger.io/
