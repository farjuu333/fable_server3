Project Name
Fable Server
client live :https://fable-client3.vercel.app
server live :https://fable-server3.onrender.com
Purpose
Fable Server is the backend API service for the Fable Ebook Platform. It provides a robust RESTful API for managing ebooks, user authentication, transactions, bookmarks, and payment processing. The server acts as the bridge between the frontend application and the MongoDB database, handling all business logic, data persistence, and third-party integrations.
E-book Management
CRUD Operations: Full support for creating, reading, updating, and deleting e-books.Advanced Search & Filtering: Users can search by title or author, filter by specific genres, and sort by price (low/high) or date.
Pagination: Data is served with pagination (defaulting to 6 items per page) for better performance.
Featured Section: A dedicated endpoint to fetch the latest 6 published books for the home page.
Payments & Transactions
Stripe Integration: Secure checkout process to purchase e-books.
Transaction Tracking: Automatically records successful purchases in a dedicated transaction database, updates the e-book's status to "sold," and assigns the buyer's email.
User Features
Purchased Library: Users can view a list of all e-books they have bought.
Bookmark System: Users can save (bookmark) books to a personal list and remove them whenever they want.
Writer Dashboard
Inventory View: Writers can view all the books they have created.
Sales Tracking: A dedicated section for writers to monitor their sales performance and revenue-generating books.
Admin Control
Content Moderation: Admins can view all books (both published and unpublished) and toggle their status.
User Management: Admin access to view all users, modify their roles (e.g., changing from user to writer), and delete accounts.
Transaction Oversight: Access to the recent transaction history of the entire platform.
Analytics & Utilities
Dashboard Stats: Provides high-level business intelligence, including total published books, total sales count, and total revenue calculated via MongoDB aggregation.
Image Uploads: Built-in functionality to upload e-book covers using the ImgBB API.
