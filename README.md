# Grocery-List-Expiry-Reminder-App
Grocery List &amp; Expiry Reminder App is an Android application designed to help users manage their grocery items efficiently. Users can create grocery lists, set expiry dates for perishable items, and receive notifications before items expire.

Features:
User authentication (Login/Signup)
Grocery list management (Add/Edit/Delete items)
Expiry date tracking with notifications
Categorization of grocery items
Cloud synchronization using a web API
Barcode scanning for easy item entry (future enhancement)

Technologies Used:
Android-Java
Retrofit for API calls
Firebase Authentication & Firestore (or any selected web service)
SQLite Database with Content Provider for local storage
AlarmManager & BroadcastReceiver for expiry reminders
Material UI Components for better user experience

App Structure:
The application consists of the following key components:
Activities & Fragments:
MainActivity - Entry point of the app, displays grocery lists.
AddItemActivity - Allows users to add new grocery items.
ItemDetailActivity - Displays details of a selected item.
SettingsFragment - Provides user settings and preferences.

Data Models:
User - Represents user account details.
GroceryItem - Represents an individual grocery item with attributes like name, category, expiryDate, and quantity.

Services & Repositories:
ApiService - Handles API requests using Retrofit.
DatabaseHelper - Manages local storage using SQLite.
NotificationManager - Handles expiry reminders and notifications.
GroceryContentProvider - Provides structured access to grocery data.

Wireframes:
The wireframes for the app's UI are stored in the wireframes/ folder. These include:
Grocery List Screen
Add Item Screen
Item Detail Screen
Settings Screen

Class Diagram:
The UML class diagram outlining the structure of the application is located in the class_diagram/ folder.

Web Service URL:
This app connects to the following web service:
Firebase Firestore API: https://firestore.googleapis.com/v1/... (or another selected API)

Installation:
Clone the repository.
Open in Android Studio.
Configure API keys if required.
Run the app on an emulator or a physical device.

Future Enhancements:
Implement barcode scanning for item entry.
Add support for sharing grocery lists.
Introduce AI-based suggestions for frequently bought items.
