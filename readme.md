# Neuroshow Platform

**Description:**  
Neuroshow is an educational platform designed to enhance learning through flashcards and quizzes with a spaced repetition system.  
Users can create flashcards with images, set difficulty levels, and receive review notifications based on their performance.

**Difficulty-based review logic:**

- **Hard:** review notification after 1 day
- **Medium:** after 3 days
- **Easy:** after 5 days

Notifications are sent directly to the user's mobile device, promoting efficient memory consolidation over time.

## Technologies used

**Web Platform:**

- **Frontend:** React.js + TailwindCSS
- **Backend:** Node.js
- **Database:** Firebase Firestore

**Mobile Applications:**

- **Android:** Kotlin with WebView integration
- **iOS:** Swift with WebView integration

**Messaging and Notifications:**

- **Cloud Messaging:** Firebase Cloud Messaging (FCM)
- **Real-time Scheduling:** Redis for temporary storage and RabbitMQ for asynchronous message dispatch to FCM tokens.

## My Contributions

- Developed the fullstack web application using React.js, TailwindCSS, and Node.js.
- Built the mobile applications for Android (Kotlin) and iOS (Swift) using WebView integration for seamless web experience.
- Designed and implemented the cloud notification system based on Redis and RabbitMQ to handle scheduled flashcard reviews.
- Integrated Firebase Authentication, Firestore Database, and Firebase Cloud Messaging (FCM) for user management and push notifications.
- Created difficulty-based spaced repetition algorithms to enhance learning efficiency.

## Private Repository Notice

Due to confidentiality agreements and project privacy, the full source code of Neuroshow cannot be shared publicly.  
Please feel free to contact me for more information during interviews.
