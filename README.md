# GreenCart
 GreenCart is an innovative e-commerce platform dedicated to promoting sustainable living by connecting consumers with eco-friendly products. Our goal is to create a marketplace that not only offers a wide range of environmentally responsible products but also educates and engages users in sustainable practices.

### Table of Contents
### Features
###  Technologies Used
### Installation
### Usage
### API Documentation
### Contributing

### Features
User -Friendly Interface: A clean, modern design that enhances user experience and simplifies navigation.
Extensive Product Range: A diverse selection of eco-friendly products across various categories, including:
Home Goods
Personal Care
Clothing and Accessories
Food and Beverages
Secure Payment Options: Multiple payment gateways (e.g., PayPal, Stripe) to ensure secure transactions.
Order Tracking: Users can track their orders in real-time, receiving updates via email and SMS.
User Reviews and Ratings: Customers can leave feedback and rate products, helping others make informed decisions.
Community Forum: A dedicated space for users to discuss sustainability topics, share tips, and connect with like-minded individuals.
Wishlist Functionality: Users can save products for future purchases, making it easier to plan eco-friendly shopping.
Blog Section: Articles and resources on sustainable living, product usage, and environmental impact.
### Technologies Used
Frontend
HTML5: For structuring the web pages.
CSS3: For styling and layout.
JavaScript: For dynamic content and interactivity.
React.js: A powerful library for building user interfaces.
Redux: For state management, ensuring a smooth user experience.
Bootstrap: For responsive design and mobile-first development.
Axios: For making HTTP requests to the backend API.
Backend
Node.js: A JavaScript runtime for building scalable server-side applications.
Express.js: A web application framework for Node.js, simplifying the server setup.
MongoDB: A NoSQL database for storing product and user data.
Mongoose: An ODM (Object Data Modeling) library for MongoDB, providing a schema-based solution.
JSON Web Tokens (JWT): For secure user authentication and authorization.
bcrypt: For hashing passwords to enhance security.
Deployment
Heroku: For hosting the application, providing a cloud platform for deployment.
GitHub: For version control and collaboration.
#### Installation
To set up the GreenCart project locally, follow these steps:

### Clone the repository:

bash
Run
Copy code
git clone https://github.com/anjalitak-dev/GreenCart.git
Navigate to the project directory:

bash
Run
Copy code
cd GreenCart
Install backend dependencies:

bash
Run
Copy code
cd backend
npm install
Install frontend dependencies:

bash
Run
Copy code
cd ../frontend
npm install
Set up environment variables: Create a .env file in the backend directory and add the following variables:

Run
Copy code
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
Start the backend server:

bash
Run
Copy code
cd backend
npm start
Start the frontend application: Open a new terminal, navigate to the frontend directory, and run:

bash
Run
Copy code
cd frontend
npm start
Access the application: Open your web browser and go to http://localhost:3000 to access the application.

###  Usage
Creating an Account: Users can sign up by providing their email and creating a password. Verification may be required.
Browsing Products: Navigate through categories to explore eco-friendly products.
Adding to Cart: Users can add items to their cart and view the total price.
Checkout Process: Users can proceed to checkout, enter shipping information, and select a payment method.
Order Confirmation: After placing an order, users receive a confirmation email with order details.
Engaging with the Community: Users can participate in discussions in the community forum and read blog articles.
