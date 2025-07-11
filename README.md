# Book Stock Management System

## Overview
The Book Stock Management System is a Spring Boot web application designed for the Royal University of Phnom Penh (RUPP) project. It enables efficient management of a bookstore's inventory, supporting two user roles: Owners and Users. Owners can oversee stock by adding, editing, and deleting books, as well as managing categories, while Users can browse, search, and purchase books. The system includes a RESTful API for programmatic access and optional image upload functionality for book covers.

## Features
### Owner Features
- **Book Management**:
  - Add new books with details (title, author, price, quantity, image).
  - Edit existing book information.
  - Delete books from inventory.
- **Category Management**:
  - Add new categories (e.g., Fiction, Non-Fiction).
  - Delete categories.
- **Dashboard**: View a consolidated list of all books and categories.

### User Features
- **Browse Books**: View books filtered by category.
- **Search Books**: Search by title or author.
- **Purchase Books**: Buy books with quantity selection, updating stock levels.

### General Features
- **Inventory Tracking**: Real-time updates to book quantities upon purchase.
- **REST API**: Endpoints for CRUD operations (e.g., `/owner/api/books` for stock management).
- **Image Support**: Optional upload of book images to AWS S3 or local storage.
