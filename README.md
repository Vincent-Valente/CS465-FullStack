# Travlr Getaways

Travlr Getaways is a full-stack web application designed to facilitate travel bookings. With distinct customer-facing and admin interfaces, the platform ensures a fluid user experience for trip searches, booking, and itinerary management, while providing admins with robust tools for content maintenance.

## Architecture
- **MongoDB**: NoSQL database for flexible data storage
- **Express.js**: Web application framework for Node.js
- **Angular**: Dynamic front-end framework
- **Node.js**: JavaScript runtime for scalable backend

## Prerequisites
- Git
- Node.js
- MongoDB
- Angular CLI

## Features
- Dynamic Booking: Customers can search, book, and review travel packages with ease.
- Admin Management: A secure and intuitive admin interface for content management.
- Responsive Design: A seamless experience across all devices.
- Robust Security: Utilizing JWT for secure authentication of admin operations.

## Getting Started
1. Clone the repository: `git clone [repository-url]`
2. Install dependencies: `npm install`
3. Start the backend: `nodemon server`
4. Launch the admin front-end: navigate to `app_admin` and run `ng serve`

## Screenshots
# Home Page
![main page](https://github.com/Vincent-Valente/CS465-FullStack/assets/125837373/6251e855-f071-479d-aea2-af4ad3282847)
# Login Page
![login](https://github.com/Vincent-Valente/CS465-FullStack/assets/125837373/ac73fbff-f473-43c7-9633-fb117cc75665)
# Logged in/out Trips Page
![Logged In](https://github.com/Vincent-Valente/CS465-FullStack/assets/125837373/2bf70a22-bef4-431f-b96c-ec8ba88858e8)
![logged out user](https://github.com/Vincent-Valente/CS465-FullStack/assets/125837373/c5126636-bc8c-4b39-a02f-ef8f0dd06568)
# Add Trip
![add](https://github.com/Vincent-Valente/CS465-FullStack/assets/125837373/02b84678-75ca-4213-99ef-42eb83dbf81a)

## Reflection

The development of Travlr  Getaways was an insightful journey that not only challenged my technical skills but also broadened my perspective on building modern web applications. Working with MEAN technologies reinforced my understanding of the MVC pattern and the significance of choosing the right stack for the required functionality. The backend, based on Node.js and Express, was efficient, while MongoDB's flexibility was a perfect fit for our dynamic data needs. On the frontend, employing Angular for the admin SPA transformed the user experience into something seamless and interactive. This was a contrast to the initial server-rendered customer pages, highlighting the trade-offs between initial load times and interactivity. Securing the application with JWT was perhaps the most crucial step, ensuring that both our customer data and administrative functionalities were protected against unauthorized access. This implementation of security measures was a practical lesson in safeguarding web applications.

Overall, this project has been pivotal in advancing my full stack development capabilities. It has honed my problem-solving skills, my ability to integrate various technologies, and my understanding of security in web applications.

