# EasyVote mobile Application

## Overview

The Voting Application is a mobile app designed to help organizations make decisions efficiently by creating and managing polls. Users can log in, create polls, vote on them, and manage polls within groups. Poll admins can view results graphically using charts and graphs. Built using Java in Android Studio, the app integrates with Firebase for backend services and utilizes MPAndroidChart for graphical data representation.

## Features

- **User Authentication**: Secure login and user management to ensure that only authorized users can access the app.
- **Poll Creation**: Allows users to create and manage polls, including setting questions and possible answers.
- **Voting**: Users can participate in polls and view real-time updates on poll results.
- **Group Polls**: Create and manage polls within user-defined groups, facilitating organization-specific decision-making.
- **Poll Results Visualization**: Graphical representation of poll results using charts and graphs for easy interpretation.
- **Admin Dashboard**: Poll creators (admins) can access a dashboard to view detailed and graphical results of polls.

## Technologies Used

- **Android Studio**: Development environment for building and running the Android application.
- **Java**: Primary programming language used for developing the app.
- **Firebase**: Provides backend services including database management and user authentication.
- **MPAndroidChart**: A library used for creating charts and graphs to visualize poll results.
- 
## ScreenShots

### Login Screen
![Login Screen](screenshots/login_screen.png)

### Poll Creation
![Poll Creation](screenshots/poll_creation.png)

### Poll Results
![Poll Results](screenshots/poll_results.png)

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/Dilan012/EasyVote-Android-App.git
    ```

2. **Open the Project**:
    - Launch Android Studio.
    - Select "Open an existing project".
    - Navigate to the cloned repository folder and open it.

3. **Setup Firebase**:
    - Follow the Firebase setup instructions to integrate your project with Firebase.
    - Add `google-services.json` to the `app` directory in your project.

4. **Add Dependencies**:
    - Ensure the required dependencies are included in your `build.gradle` file:
      ```groovy
      implementation 'com.google.firebase:firebase-auth:21.0.5'
      implementation 'com.google.firebase:firebase-database:20.0.5'
      implementation 'com.github.PhilJay:MPAndroidChart:v3.2.0'
      ```

5. **Run the Application**:
    - Connect your Android device or use an emulator.
    - Click "Run" in Android Studio to build and deploy the app.

## Usage

1. **Log In**:
    - Open the app and log in using your credentials or sign up if you're a new user.

2. **Create a Poll**:
    - Go to the poll creation section.
    - Enter the poll details and options, then submit.

3. **Vote on Polls**:
    - enter poll id or link to the specific poll and vote for it. poll id or link should get via the poll creator. group poll are available for all the group members

4. **Manage Groups**:
    - Create and manage groups to organize and categorize polls effectively.

5. **View Poll Results**:
    - Poll admins can view results in the results section, where graphical charts and graphs provide a clear summary of poll outcomes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or inquiries, please contact Dilan at dilanmadusanka5555@gmail.com.
