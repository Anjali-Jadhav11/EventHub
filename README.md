# EventHub
EventHub is a modern JavaFX-based event management application designed to simplify event creation, organization, and booking.
It allows organizers to post event details and users to explore, book, and manage their participation.
The system uses Firebase Firestore for real-time data storage and synchronization.

>> Features
>> User Features

User Sign Up and Login (with Firebase Authentication)
View and book upcoming events
Edit personal profile information
View booking history

>> Organizer Features

Organizer Sign Up and Login
Add new events with name, date, time, and location
Manage and update existing events
View attendees for each event

>> Admin / Backend

Firebase Firestore used as cloud database
Real-time updates across user and organizer dashboards

EventHub/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   ├── controllers/         # JavaFX controller classes
│   │   │   ├── models/              # User and Event model classes
│   │   │   ├── firebase/            # Firebase configuration and Firestore service
│   │   │   ├── views/               # FXML UI files
│   │   │   ├── EventHub.java        # Main application entry point
│   │   │   ├── EventDetailsPage.java
│   │   │   ├── UserSignUpPage.java
│   │   │   ├── OrganizerSignUp.java
│   │   │   └── UserProfilePage.java
│   │   └── resources/
│   │       ├── fxml/                # All FXML layout files
│   │       └── css/                 # Styling files
│   └── test/                        # Unit and integration tests
│
├── firebase.json                    # Firebase configuration
├── pom.xml / build.gradle            # Dependency file
└── README.md

