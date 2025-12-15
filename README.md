Weight Tracker App - Portfolio Submission by Nidhi Shree

Welcome to my portfolio! This repository showcases my work for mobile architect and programmimg, specifically focusing on my development of the Weight Tracker App. As a Mobile Architecture student, I’ve aimed to design and develop an app that helps users track their weight and achieve fitness goals. This project includes both the user interface (UI) design from Project Two and the app's code development from Project Three, which are now combined into a fully functional mobile app.

Summary of App Requirements and Goals

The Weight Tracker App is designed to address the need for a simple yet effective tool for tracking personal weight progress. It allows users to log their daily weight, set a target goal, and receive notifications when they reach their desired weight. The app serves the user’s need to stay motivated and track fitness progress over time, helping them achieve their health and weight management goals.

UI Design and Features

To support the user’s needs, I created several screens and features:

Login Screen: Allows users to sign in or create a new account.

Weight Log Screen: Displays a list of past weights in a grid, with an option to add new weights.

Add Weight Screen: Allows users to input their current weight.

Goal Setting Screen: Users can set and view their target weight.

SMS Notification Feature: Notifies users via SMS when they reach their goal weight (optional).

Logout Feature: Allows users to log out and end their session.

The user-centered UI design keeps the user’s needs at the forefront by making it easy to log data, track progress, and receive motivational alerts. The app’s simple design, minimal navigation, and clear labels ensure that users of all technical backgrounds can use it effectively. The design has been successful in providing a clear, streamlined experience that encourages consistent app usage.

Approach to Coding the App

When approaching the coding of the app, I used a modular approach to keep the code clean and maintainable. Key strategies included:

Breaking down the app into clear, independent components (e.g., login screen, weight log screen, goal screen).

Using Roma tools (using SQLite) to store user data (weight logs and goals) locally on the device.

Implementing user input validation and error handling to ensure a smooth user experience.

For future projects, these strategies can be applied to improve code reusability, scalability, and maintainability. Modularizing the code ensures that updates and new features can be added with minimal disruption to existing functionality.

Testing and Functionality

To ensure the app was functional, I performed extensive testing using both the Android Emulator and real devices. The main testing strategies included:

Unit testing individual app components (e.g., database operations, input validation).

User acceptance testing (UAT) to verify that the app meets user requirements (e.g., easy navigation, intuitive UI).

Permission testing to ensure SMS notifications work correctly when granted or denied by the user.

This testing process is essential because it helps identify and resolve bugs before release, ensuring a smooth user experience. It revealed that while the core features worked well, I needed to refine how the app handled permission requests for SMS notifications, ensuring the app could still function without those permissions.

Innovation and Challenges

Throughout the app development process, I encountered several challenges, such as:

Implementing the SMS notification feature: This required careful handling of user permissions and ensuring that the app could still function without this feature if the user denied permission.

Logical implmentation of the weight tracking grid, sorting the entries realtime and ability to edit/update/delete weight entries with smooth transition was a challenging aspect.

Designing a simple yet functional UI: Balancing simplicity with functionality required iterative design and testing.

I had to innovate by researching and applying best practices for mobile notifications and ensuring the app’s database structure was scalable enough to handle future updates.

Areas of Success

I am particularly proud of my database implementation and how I managed to structure it to support persistent user data. The ability to save weight logs, set goals, and retain data across sessions was a key feature that demonstrated my understanding of mobile database management. I also successfully integrated SMS notifications, which was an advanced feature that added real-world value to the app.

Learnings from Project Three: weight tracker app

In Project Three, I gained valuable experience handling runtime permissions (like SEND_SMS), ensuring the app requests necessary permissions during runtime, not just in the manifest. I also learned how to preserve app data using onSaveInstanceState, which allowed me to maintain critical information (such as phone number and weight) when the activity was recreated. Additionally, I implemented the Room Persistence Library for managing the SQLite database, using background threads to avoid blocking the UI. These skills improved my ability to build more reliable and efficient mobile apps

This project allowed me to apply key principles of mobile app development, including UI/UX design, database management, and functional coding. It also gave me experience in testing, debugging, and refining my work to create a user-friendly mobile app. I look forward to continuing my growth in mobile app development and showcasing my future projects.

