# Alexandria App :books:
A search mobile app using Google Books API, Firebase Auth, Firestore Database, and HTTP Requests to create a book review platform.

## Features :sunglasses:	
- Manages the search for books through the Google Books API.
- Create users through Firebase Auth with their email address, full name and password information.
- Request access to the app through Firebase Auth to login to the search manager.
- Displays an initial search of Google Books books by making HTTP requests to the API.
- Lazy loading scroll implemented using Provider for the results obtained.
- Allows the user to search for any desired book.
- Tapping on a specific book allows the user to obtain author information, description and a cover image. 
- Save desired books in favorites through Firestore Database.
- Review user information and end the session.
- Review your favorites list and delete the desired ones from it.


### Extras :heavy_plus_sign:
- Verify that the email for registration and access is a valid email.
- Verify that the password is longer than 7 characters and has at least one special character.
- Disables access or registration options until the data has been verified as correct.
- Replaces the remaining information in any book to ensure null sound safety.


## Technologies :man_technologist:	
- Cloud Firestore.
- Email Validator.
- Firebase Authentication.
- Cloud Storage.
- Provider.
- HTTP.
- Form Field Validator.

### Deployment
- Cupertino Library.
- Flutter_launcher_icons.
- Model View Controller Architecture.

## Installation Requirements :arrow_down:
- Android 5.0
- Android Devices
- Flutter Version 3.3.10
