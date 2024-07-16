# Ellemora-Mobile-App
Ellemora is a Flutter-based e-commerce application that allows users to browse and purchase products from the FakeStore API. It includes features such as user authentication, product listing, category filtering, search functionality, and cart management with persistent storage.

Tech Stack
Flutter
Firebase Authentication
Firebase Firestore (Storage)
Provider (for state management)
Razorpay Flutter SDK

**Features**

**User Authentication**

Users can sign up or log in to access the app.
Firebase Authentication is used for secure user authentication.

**Product Listing**
Displays products fetched from the FakeStore API.
Supports categorization and filtering using button tab bars.

**Product Details**
Provides detailed information about each product.
Users can add products to their carts directly from the product detail page.

**Cart Management**
Allows users to add products to their cart.
Cart items are stored in a database (Firebase Firestore) and persist across user sessions.

**Buy Now with Razorpay**
Integration with Razorpay for secure and seamless payment processing.
Users can proceed to buy products directly from their cart.

**Search Functionality**
Enables users to search for specific products by name.
Real-time filtering of products based on search queri
