# Item Renting Website

## Project Overview

This project is an item renting website designed to facilitate the rental of various items. Users can browse available items, place rental requests, and manage their rental orders through the platform.

## Features

- **User Authentication**: Secure user registration and login.
- **Item Listings**: Browse and search available items for rent.
- **Rental Requests**: Users can request to rent items.
- **Order Management**: Users can view and manage their rental orders.
- **Admin Panel**: Admins can manage item listings, rental requests, and users.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Token)

## Installation

 Clone the repository:

   ```bash
   git clone https://github.com/Mitesh9047/item_Renting_website.git
   cd item_Renting_website
   ```


## Install all dependencies
```bash
npm install
```
## Set up the environment variables:
Create a .env file in the root directory and add the following:
```env
PORT=3000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```
## Start the server:

```bash
npm start
```
The server will start running on http://localhost:3000.

## Usage
Open your browser and navigate to http://localhost:3000.
Register a new user account or log in with an existing account.
Browse available items for rent.
Place a rental request for an item.
Manage your rental orders from your profile.
Project Structure
```arduino
.
├── public
│   ├── css
│   ├── js
│   └── images
├── routes
│   ├── api.js
│   ├── auth.js
│   └── index.js
├── views
│   ├── partials
│   ├── index.ejs
│   ├── login.ejs
│   ├── register.ejs
│   └── dashboard.ejs
├── .env
├── app.js
├── package.json
└── README.md
```
