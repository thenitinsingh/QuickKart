# QuickKart 

**A Full-Stack Quick Commerce Application**

QuickKart is a quick-commerce web application designed to provide users with a seamless online shopping experience. Inspired by modern instant-delivery platforms, the project aims to bring product discovery, browsing, and shopping functionalities together through a clean and responsive interface.

The application is being developed using **React, Flask, and MongoDB**, with a focus on building a modular, scalable, and maintainable full-stack architecture.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React.js |
| Backend | Python, Flask |
| API Architecture | REST APIs |
| Database | MongoDB |
| Styling | CSS |
| Data Format | JSON |
| Version Control | Git & GitHub |

### Architecture

QuickKart follows a client-server architecture:

- **Frontend (React):** Responsible for the user interface, product presentation, and user interactions.
- **Backend (Flask):** Handles API requests, application logic, and communication with the database.
- **Database (MongoDB):** Stores product information, categories, pricing, descriptions, and image references.

The frontend communicates with the backend through RESTful APIs, while Flask interacts with MongoDB to retrieve and manage application data.

---

## Planned Features

The application is being developed with the following functionalities in mind:

- **Product Listing:** Display products dynamically using data retrieved from backend APIs.
- **Product Details:** Present product names, descriptions, pricing, categories, and images.
- **Product Search:** Enable users to find products based on their names or relevant keywords.
- **Product Sorting:** Organize products based on parameters such as price and popularity.
- **Shopping Cart:** Provide an interface for managing selected products.
- **Responsive UI:** Deliver a consistent shopping experience across different screen sizes.
- **REST API Integration:** Establish communication between the React frontend and Flask backend.
- **Database Integration:** Persist and retrieve product information using MongoDB.

Additional functionalities may be introduced as the project evolves.

---

## Project Structure

The intended project structure will follow a modular separation of frontend and backend components.

```text
QuickKart/
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── App.jsx
│   │   └── main.jsx
│   │
│   ├── package.json
│   └── .env
│
├── backend/
│   ├── app/
│   │   ├── routes/
│   │   ├── models/
│   │   ├── services/
│   │   └── __init__.py
│   │
│   ├── config/
│   ├── app.py
│   ├── requirements.txt
│   └── .env
│
├── .gitignore
└── README.md
```

*Note: This represents the intended project structure and may evolve during development.*

---

## Getting Started

The application is currently under development. Setup instructions will be updated as the frontend, backend, and database components are integrated.

### Prerequisites

Ensure the following tools are available in your development environment:

- Python 3.x
- Node.js and npm
- MongoDB
- Git

### Installation

Clone the repository:

```bash
git clone https://github.com/thenitinsingh/QuickKart.git
```

Navigate to the project directory:

```bash
cd QuickKart
```

Frontend and backend installation and execution instructions will be added as their respective implementations are finalized.

---

## Development Roadmap

- [x] Initial Flask REST API prototype
- [x] Product listing UI reference template
- [ ] React frontend implementation
- [ ] Flask backend modularization
- [ ] MongoDB database integration
- [ ] Dynamic product listing through REST APIs
- [ ] Product search and sorting
- [ ] Shopping cart functionality
- [ ] Frontend-backend integration
- [ ] Testing and deployment

---

## Project Objective

The primary objective of QuickKart is to gain practical experience in full-stack application development by integrating a modern frontend framework with a Python-based REST API backend and a NoSQL database.

The project also provides an opportunity to explore API design, database integration, frontend-backend communication, and real-world application architecture.

---

## Project Status

**Currently under development.**

This repository will be updated progressively as new features and components are implemented.

---

## Author

**Nitin Singh**
