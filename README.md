# ecomm-full-stack
# Table of Contents

- [About](#about)
- [Getting Started](#getting-started)
- [Deployment](#deployment)
- [Usage](#usage)
- [Built Using](#built-using)
- [TODO](#todo)
- [Contributing](#contributing)
- [Authors](#authors)
- [Acknowledgments](#acknowledgments)

## About
Welcome to our eCommerce website project! This platform is designed to provide users with a seamless online shopping experience. It offers a wide range of products and integrates the Razorpay payment gateway for secure and reliable payment processing.

## Getting Started
To run this project locally for development and testing purposes, follow these steps:

### Prerequisites
- Eclipse IDE installed on your system.
- Java Development Kit (JDK) installed.

### Installing
1. Clone the repository:
git clone https://github.com/riyakasaudhan20/ecomm-full-stack.git

2. Backend Setup:
- Open Eclipse IDE and import the backend project:
  - File > Import > Existing Maven Projects
  - Select the `ecommerce-website/backend` directory.
  - Click "Finish" to import the project.

- Resolve Maven dependencies:
  - Eclipse will automatically download the required dependencies specified in the `pom.xml` file.

- Run the Spring Boot application:
  - Open the main class, usually named `EcommerceWebsiteApplication.java`.
  - Right-click on the file and select "Run As" > "Java Application".
  - The Spring Boot application will start, and you should see log messages indicating that the application has started successfully.

## Running the tests
To run automated tests for this system, follow the steps below:

### End-to-End Tests
- Explain what these tests test and why.

Example:
mvn spotless:check

## Usage
Once the backend Spring Boot application is running, it will serve as the backend for the frontend React application. Users can interact with the website's frontend to browse products, add items to the cart, and proceed with the checkout process using the integrated Razorpay payment gateway.

## Deployment
To deploy this project on a live system, follow these steps:

1. Set up a MySQL database to store product information and user data.

2. Build the frontend for production:
cd ecommerce-website/frontend
npm run build

3. Deploy the backend Spring Boot application to a suitable application server, such as Tomcat.

4. Configure the necessary environment variables for both frontend and backend, such as database credentials and Razorpay API keys.

5. Launch the website on the production server.

## Built Using
- React: JavaScript library for building user interfaces.
- Spring Boot: Java-based framework for building robust and scalable applications.
- MySQL: Relational database management system for data storage.
- Razorpay: Payment gateway for secure and seamless online transactions.

## TODO
- Implement user authentication and user profiles.
- Add support for multiple payment gateways.
- Enhance the frontend design and user interface.
- Implement product rating and review system.

## Contributing
We welcome contributions to this project! If you would like to contribute, please follow the standard GitHub workflow by forking the repository and creating a pull request. Make sure to read our contributing guidelines for more details.

## Authors
- [Riya kasaudhan](https://github.com/riyakasaudhan20) - Lead Developer and Project Owner

## Acknowledgments
Special thanks to the developers and contributors of the open-source libraries and frameworks used in this project. Their hard work and dedication make projects like this possible.
