# SHUber - Sheffield Hallam University's Ride-Sharing App
Overview
SHUber is a ride-sharing Android application developed for the Sheffield Hallam University student community. Inspired by Uber, SHUber connects riders with drivers within the university area, providing a convenient, safe, and accessible transportation option. The app incorporates features tailored to the specific needs of the university's diverse community, including support for individuals with special needs.

Project Structure
app: Main application module containing all the source code, resources, and configuration files.
firebase: Integration files for Firebase, used for authentication, database, and storage solutions.
models: Data models representing users (riders and drivers), trips, and feedback.
views: Activity and fragment files for the user interface.
controllers: Logic for handling user inputs, Firebase interactions, and navigation.
utils: Utility classes for location services, notifications, and other shared functionalities.
Key Features
Rider and Driver Accounts: Separate account types for riders and drivers, with the ability to request rides and accept ride requests, respectively.
Special Needs Support: Features to accommodate riders with special needs, such as wheelchair-accessible vehicles.
Real-Time Notifications: Real-time updates for ride status, driver location, and trip completion.
Firebase Backend: A robust backend built on Firebase for user authentication, real-time database updates, and storage.
Getting Started
Prerequisites
Android Studio 4.0 or higher
Firebase account for backend setup
Google Maps API key for location services
Setup
Clone the repository:
bash
Copy code
git clone 
Open the project in Android Studio:
Start Android Studio and select "Open an existing Android Studio project".
Navigate to the cloned repository and open it.
Configure Firebase:
Create a new Firebase project in the Firebase console.
Add an Android app to your Firebase project and follow the setup instructions.
Download the google-services.json file and place it in the app directory of the project.
Set up Google Maps API:
Obtain a Google Maps API key by following the instructions here.
Add your API key to the AndroidManifest.xml file.
Running the App
After configuration, build and run the app on an emulator or connected device via Android Studio.
Contribution Guidelines
To contribute to SHUber, please follow the Scrum methodology for agile development. Create a branch for each feature or fix, submit pull requests, and ensure thorough testing before merging.

Acknowledgements
I'd like to thank Sheffield Hallam University's Department of Computing for the opportunity to work on this project. Special thanks to our instructors and peers for their guidance and feedback throughout the development process.