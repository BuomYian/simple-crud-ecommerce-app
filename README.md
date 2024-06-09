# E-Commerce CRUD Web App

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232a?style=for-the-badge&logo=react&logoColor=61dafb)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

This project is a simple CRUD e-commerce web application built using Next.js. It allows users to browse products, add new products, edit existing products, and delete products. This app is ideal for demonstrating the basic functionality of a modern e-commerce platform.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Configuration](#configuration)
  - [Running the App](#running-the-app)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- Browse products with a user-friendly interface.
- Add new products with essential details like name, description, price, and image.
- Edit details of existing products.
- Delete products from the catalog.
- Responsive design for mobile and desktop.

## Technologies

- [Next.js](https://nextjs.org/) - The React Framework for Production
- [React](https://reactjs.org/) - A JavaScript library for building user interfaces
- [Node.js](https://nodejs.org/) - JavaScript runtime built on Chrome's V8 JavaScript engine
- [Express](https://expressjs.com/) - Fast, unopinionated, minimalist web framework for Node.js
- [MongoDB](https://www.mongodb.com/) - NoSQL database for modern applications
- [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework for rapid UI development

## Prerequisites

- Node.js (v13 or later)
- npm (v6 or later) or yarn (v1.22 or later)
- MongoDB (local or cloud instance)

## Getting Started

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/BuomYian/simple-crud-ecommerce-app.git
   cd simple-crud-ecommerce-app
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

### Configuration

1. Create a `.env.local` file in the root directory and add the following environment variables:

   ```env
   MONGODB_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/mydatabase?retryWrites=true&w=majority
   NEXT_PUBLIC_API_URL=http://localhost:3000/api
   ```

   Replace `<username>`, `<password>`, and `mydatabase` with your actual MongoDB credentials and database name.

### Running the App

1. Start the development server:

   ```bash
   npm run dev
   # or
   yarn dev
   ```

2. Open your browser and navigate to `http://localhost:3000`.

## Usage

- **View Products:** Access the home page to see a list of products.
- **Add Product:** Click on "Add Product" to create a new product entry.
- **Edit Product:** Click on the edit icon next to a product to modify its details.
- **Delete Product:** Click on the delete icon next to a product to remove it from the list.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your changes. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

- **Name:** Your Name
- **Email:** buom.nyajal@gmail.com
- **GitHub:** [your-username](https://github.com/BuomYian)
