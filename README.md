# E-Commerce CRUD Web App

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007acc?style=for-the-badge&logo=typescript&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-1B222D?style=for-the-badge&logo=prisma&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Material UI](https://img.shields.io/badge/Material--UI-0081CB?style=for-the-badge&logo=mui&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448c5?style=for-the-badge&logo=cloudinary&logoColor=white)

This project is a simple CRUD e-commerce web application built with Next.js, TypeScript, Prisma, MySQL, Material UI, and Cloudinary. It allows users to manage products through a clean, user-friendly interface, and supports basic e-commerce functionality.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Configuration](#configuration)
  - [Running the App](#running-the-app)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Product Management:** Create, read, update, and delete products.
- **Image Upload:** Integrates Cloudinary for image storage and management.
- **Responsive Design:** Utilizes Material UI for a modern, responsive interface.
- **Typed Codebase:** Built with TypeScript for type safety and improved development experience.

## Technologies

- **[Next.js](https://nextjs.org/)** - React framework for server-side rendering and static site generation.
- **[TypeScript](https://www.typescriptlang.org/)** - Typed superset of JavaScript for writing safer and more scalable code.
- **[Prisma](https://www.prisma.io/)** - Next-generation ORM for MySQL and other databases.
- **[MySQL](https://www.mysql.com/)** - Relational database management system.
- **[Material UI](https://mui.com/)** - React component library for faster and easier web development.
- **[Cloudinary](https://cloudinary.com/)** - Cloud-based service for image and video management.

## Prerequisites

- Node.js (v14 or later)
- npm (v6 or later) or yarn (v1.22 or later)
- MySQL (local or cloud instance)
- Cloudinary account

## Getting Started

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/simple-crud-ecommerce-app.git
   cd simple-crud-ecommerce-app
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

### Configuration

1. Create a `.env` file in the root directory and add the following environment variables:

   ```env
   DATABASE_URL="mysql://user:password@localhost:3306/mydatabase"
   CLOUDINARY_CLOUD_NAME=your_cloud_name
   CLOUDINARY_API_KEY=your_api_key
   CLOUDINARY_API_SECRET=your_api_secret
   NEXTAUTH_SECRET=your_nextauth_secret
   ```

   Replace the placeholders with your actual MySQL credentials and Cloudinary API details. Generate a random value for `NEXTAUTH_SECRET` using a generator like `openssl rand -base64 32`.

2. Generate the Prisma client:

   ```bash
   npx prisma generate
   ```

3. Run Prisma migrations to set up your database schema:
   ```bash
   npx prisma migrate dev --name init
   ```

### Running the App

1. Start the development server:

   ```bash
   npm run dev
   # or
   yarn dev
   ```

2. Open your browser and navigate to `http://localhost:3000`.

## Usage

- **View Products:** Visit the homepage to see a list of products.
- **Add Product:** Use the "Add Product" form to create a new product entry.
- **Edit Product:** Click on a product to view and edit its details.
- **Delete Product:** Use the delete button to remove a product from the list.

## Project Structure

```
simple-crud-ecommerce-app/
├── components/          # React components
├── pages/               # Next.js pages
│   ├── api/             # API routes
│   ├── index.tsx        # Home page
│   └── product/         # Product pages
├── prisma/              # Prisma schema
│   ├── migrations/      # Database migrations
│   └── schema.prisma    # Prisma schema file
├── public/              # Static files
├── styles/              # CSS files
├── utils/               # Utility functions
├── .env                 # Environment variables
├── next.config.js       # Next.js configuration
├── tsconfig.json        # TypeScript configuration
├── package.json         # npm/yarn configuration
└── README.md            # Project documentation
```

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

- **Name:** Buomkuoth Yian
- **Email:** buom.nyajal@gmail.com
- **GitHub:** [BuomYian](https://github.com/BuomYian)
