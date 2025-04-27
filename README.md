# EventTrackingApp_DianaGalvez
A mobile app for event management, created for CS 360
Diana Galvez Mendez

This mobile app project was designed to help users manage their events and schedules in a simple, intuitive way. The main goal was to create a lightweight event-tracking tool that focuses on user-centered design and mobile development best practices. The app allows users to easily add, view, edit, and delete events, helping them stay organized without overwhelming them with unnecessary features.

The app specifically addresses the need for a straightforward event management solution for students, working professionals, and anyone looking to simplify their day to day planning.

## Screens and Features
The app includes several core screens:
- **Login/Signup Screen**: Allows users to create an account and securely log in.
- **Dashboard Screen**: Displays all events in a clean, easy to read grid format.
- **Add Event Screen**: Lets users quickly add new events with title, date, time, and description.
- **Permission Handling**: Prompts users for SMS permissions and allows the app to continue functioning even if permission is denied.

Each screen was designed with the user’s experience in mind, prioritizing clean layouts, minimal input fields, clear button labels, and simple navigation.  
The UI designs were successful because they kept the user flow simple and intuitive, minimizing friction points and focusing on essential actions.

## Coding Process and Techniques
When coding the app, I focused heavily on modularity and clarity. Each major feature, database management, user authentication, event CRUD operations, and permission handling — was separated into manageable parts. I used helper classes like `DatabaseHelper` and maintained consistent naming conventions to keep the code organized and easy to debug.

This modular approach helped me troubleshoot and make improvements faster, and it’s a strategy I will continue to apply in future app development projects.

## Testing and Importance
Throughout the development process, I regularly tested the app using the Android Emulator. After implementing each major feature, I tested different user flows, for example, creating a new user, logging in, adding multiple events, denying SMS permission, and checking that event data persisted after closing the app.

Testing was critical because it revealed small issues early (such as needing to handle denied permissions properly) and helped ensure the app was both functional and resilient.

## Innovation and Challenges
One area where I had to innovate was ensuring full compliance with newer Android requirements, such as declaring `android:exported="true"` for activities with intent filters. Since these requirements were introduced recently, it took additional research to understand them and correctly implement them so the app would launch successfully on newer devices.

Another challenge was making sure the app still provided a smooth user experience even if permissions were denied, balancing optional features like SMS without breaking core functionality.

## Strengths and Successes
I am particularly proud of how the app’s database design and event management features turned out. The app successfully performs Create, Read, Update, and Delete (CRUD) operations on user-created events while maintaining data persistence using SQLite.

This project helped me bring together multiple mobile development skills, UI design, coding best practices, permission handling, and user-centered thinking — into a complete, working application that I am proud to showcase.

