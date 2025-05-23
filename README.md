# MiniCart - A Prototype E-commerce Solution

MiniCart is a prototype full-stack e-commerce application built with TypeScript, demonstrating modern development practices and scalable architecture. This project serves as a proof-of-concept for building e-commerce solutions with separate frontend and backend services.

## Project Overview

This prototype implements core e-commerce functionalities while maintaining a clean, modular architecture:

- **Frontend**: A modern web application built with Next.js, featuring a responsive product catalog and shopping cart
- **Backend**: A RESTful API service built with Node.js and Express, handling product management and orders

### Demo Features
- Product catalog browsing
- Shopping cart management
- Basic user authentication
- Order processing workflow

## Tech Stack

### Frontend
- Next.js
- TypeScript
- Redux for state management
- Geist UI components
- Organized component structure

### Backend
- Node.js + Express.js
- TypeScript
- MySQL with Sequelize ORM
- JSON Web Tokens (JWT)
- Express Session
- CORS enabled

## Project Structure

```
├── frontend/             # Next.js frontend application
│   ├── app/              # Next.js app directory
│   ├── components/       # Reusable UI components
│   ├── services/         # API and app services
│   ├── store/            # Redux store configuration
│   ├── types/            # TypeScript type definitions
│   └── views/            # Page-specific components
│
└── backend/             # Express.js backend API
    ├── src/              # Source code
    ├── config/           # Configuration files
    ├── controllers/      # Request handlers
    ├── models/           # Database models
    ├── routes/           # API routes
    └── services/         # Business logic
```

## Development Roadmap

### Phase 1 (Current)
- Basic product catalog
- Shopping cart functionality
- User authentication
- Order management

### Phase 2 (Planned)
- Advanced search and filtering
- Payment gateway integration
- User reviews and ratings
- Admin dashboard

### Phase 3 (Future)
- Inventory management
- Multiple payment methods
- Analytics and reporting
- Mobile app development

## Prerequisites

- Node.js (v14 or higher)
- MySQL Server
- npm or yarn package manager

## Getting Started

1. Clone the repository
```bash
git clone https://github.com/yourusername/minicart.git
cd minicart
```

2. Set up the backend
```bash
cd backend
npm install
# Configure your environment variables
npm run dev
```

3. Set up the frontend
```bash
cd frontend
npm install
npm run dev
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.