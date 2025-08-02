📚 Read Buddy

📋 Description
ReadBuddy is a Flutter-based mobile application designed for book lovers to discover and explore books across various genres. It leverages the Google Books API to fetch live data and presents it in a visually appealing format. With Firebase Authentication, users can securely sign up and log in. The app features a gradient-themed UI, categorized book display, and search functionality, providing a modern reading experience.

🧰 Technology Stack

Flutter – Cross-platform mobile app framework

Dart – Programming language used with Flutter

Firebase Authentication – For user sign-up and login

Google Books API – To fetch real-time book data

HTTP – For network requests

Material Design – For consistent and sleek UI components

🚀 How to Run the Project

✅ Prerequisites:

1. Flutter SDK (3.x.x)

2. Dart SDK

3. Firebase project configured

4. Google Books API (public key not required for basic queries)

📦 1. Clone the Repository

git clone https://github.com/your-username/readbuddy.git
cd readbuddy

📱 2. Get Dependencies

flutter pub get

🔥 3. Connect Firebase
Use firebase_options.dart (already generated via FlutterFire CLI).

Make sure your Firebase project has authentication enabled (Email/Password).

▶️ 4. Run the App

flutter run

🌟 Features
🔐 User Login & Signup using Firebase

📖 Explore Books by genre via Google Books API

🔍 Search Books by title in real time

🧑‍💼 Profile Page with user details

📚 Genre-wise Scrollable Layout for better UX

🎨 Gradient UI with animated splash screen

🧪 Screenshots
(Include screenshots here if you'd like to showcase the app UI)

📦 Folder Structure

/lib/
│
├── main.dart                 # App entry point
├── login_page.dart           # Login logic and design
├── signup_page.dart          # Signup logic and design
├── home_page.dart            # Main dashboard with books by genre
├── search_page.dart          # Book search functionality
├── book_widget.dart          # Reusable widget to display each book
├── firebase_options.dart     # Firebase config
📌 Notes
1. Replace any hardcoded UserCredential logic with FirebaseAuth.instance.currentUser if needed globally.

2. You can customize genres or extend the app to allow users to save favorite books.

Screenshots:

<img width="352" height="740" alt="f1" src="https://github.com/user-attachments/assets/a3830692-b682-4417-b4f9-077c6a268078" />
<img width="347" height="707" alt="f2" src="https://github.com/user-attachments/assets/695f80dc-2189-4ef8-9c4c-58e9dca56cd8" />
<img width="350" height="737" alt="f3" src="https://github.com/user-attachments/assets/2a3682cd-e89a-4a87-bf8a-3bc7cd40e80b" />
<img width="352" height="756" alt="f4" src="https://github.com/user-attachments/assets/83ea72ed-712f-487b-86fe-509d2db28a66" />
<img width="336" height="147" alt="f5" src="https://github.com/user-attachments/assets/c366c8f2-de0d-4056-87fd-1e9bffe1af1b" />
<img width="338" height="152" alt="f6" src="https://github.com/user-attachments/assets/87c68b51-ec03-4379-94dd-974174459249" />
<img width="348" height="708" alt="f7" src="https://github.com/user-attachments/assets/70cf2095-0603-4945-bb1c-2b5d95dbe2f2" />





