# ExploreEats - Food, Travel & Blog App

## Overview
ExploreEats is a comprehensive web application designed for wanderers to explore nearby places and restaurants, as well as write and visit blogs. Built using the MERN stack, the app offers secure authentication using JWT and CORS, making it a reliable and user-friendly platform for travelers and food enthusiasts.

## Features
1. **Explore Nearby Places**
   - **Google Places API Integration**: Fetches tourist places based on the user's search location, providing accurate and up-to-date information on local attractions.

2. **Discover Restaurants**
   - **Documenu API Integration**: Retrieves nearby restaurants based on selected cuisine, helping users find the perfect dining options tailored to their preferences.

3. **Blogging Platform**
   - **Write and Visit Blogs**: Users can create and share their travel experiences and food reviews.
   - **Comment and Social Media Share**: Enables users to comment on blogs and share their favorite posts on social media, fostering community engagement.

## Authentication
- **JWT Authentication**: Ensures secure access to user accounts and data.
- **CORS**: Protects against cross-origin requests, enhancing security.

## Technologies Used
- **MongoDB**: Database management for storing user data, blog posts, and place/restaurant information.
- **Express.js**: Server-side framework for building robust APIs and handling requests.
- **React**: Frontend library for building user interfaces and ensuring a smooth user experience.
- **Node.js**: Backend runtime environment for executing JavaScript on the server.
- **Google Places API**: Provides detailed information about places based on search criteria.
- **Documenu API**: Supplies data on restaurants based on selected cuisine.

## Skills Highlighted
- MongoDB
- Web Applications
- JavaScript
- Node.js
- Databases
- Teamwork
- Express.js

## Getting Started
### Prerequisites
- Node.js and npm installed on your machine.
- MongoDB instance running locally or on a cloud service.
- API keys for Google Places and Documenu.

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/ExploreEats.git
   cd ExploreEats
   ```

2. **Install dependencies for backend and frontend:**
   ```bash
   npm install
   cd client
   npm install
   ```

3. **Create a `.env` file in the root directory and add the following:**
   ```env
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   GOOGLE_PLACES_API_KEY=your_google_places_api_key
   DOCUMENU_API_KEY=your_documenu_api_key
   ```

4. **Run the application:**
   ```bash
   npm run dev
   ```

### Usage
- Open your browser and navigate to `http://localhost:3000`.
- Create an account or log in to start exploring places, discovering restaurants, and reading or writing blogs.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any queries or support, please contact Swini Rodrigues at rodrigues.sw@northeastern.edu.
