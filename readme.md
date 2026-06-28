Project Name
Fable Server

Purpose
Fable Server is the backend API service for the Fable Ebook Platform. It provides a robust RESTful API for managing ebooks, user authentication, transactions, bookmarks, and payment processing. The server acts as the bridge between the frontend application and the MongoDB database, handling all business logic, data persistence, and third-party integrations.
E-book Management
CRUD Operations: Full support for creating, reading, updating, and deleting e-books.Advanced Search & Filtering: Users can search by title or author, filter by specific genres, and sort by price (low/high) or date.
Pagination: Data is served with pagination (defaulting to 6 items per page) for better performance.
Featured Section: A dedicated endpoint to fetch the latest 6 published books for the home page.
. Payments & Transactions
Stripe Integration: Secure checkout process to purchase e-books.

Transaction Tracking: Automatically records successful purchases in a dedicated transaction database, updates the e-book's status to "sold," and assigns the buyer's email.