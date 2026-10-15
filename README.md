# CS-360

CS 360 Mobile Architecture and Programming projects focused on Android app development, user interface design, database integration, and mobile application functionality.

## Project Overview

For this project, I developed an Inventory App using Java in Android Studio. The goal was to create a mobile application that allows users to manage inventory, track item quantities, and receive low-stock notifications. The app was designed with warehouse employees in mind, giving them a simple way to organize inventory and keep track of available stock. It includes account creation, secure login, inventory management, and SMS notification settings.

## User Interface and Design

The app includes a login and account creation screen, an inventory screen, an add-item screen, and an SMS notification settings screen. I focused on keeping the interface simple and easy to navigate so users could access important features without unnecessary steps. The inventory screen displays stored items in a grid, making it easier to view and manage stock. I also used clearly labeled buttons and input fields to help users understand how to interact with each screen. These design choices made the app more practical and helped create a consistent experience throughout the application.

## Coding Approach

I approached the development process by breaking the application into smaller components and working on each feature individually. I started with the UI designs from Project Two and gradually added the functionality required for Project Three. I used Java for the application logic and SQLite to manage user accounts and inventory information. Keeping the database operations separate from the activity classes helped me organize the code and troubleshoot problems more efficiently. This approach taught me the importance of building and testing features individually, which is something I plan to continue doing in future software development projects.

## Testing and Functionality

I tested the application using the Android Studio emulator to make sure the main features worked correctly. My testing included creating accounts, logging in, adding inventory items, navigating between screens, and configuring SMS notification settings. I also verified that inventory information was being saved and displayed through the SQLite database. During testing, I encountered emulator performance issues that caused the system to become unresponsive. Restarting and cold booting the emulator helped resolve these problems. Although I successfully tested the SMS permission and settings functionality, I could not verify actual SMS delivery through the emulator. This experience showed me why testing is important for identifying problems and confirming that an application behaves as expected.

Challenges and Problem-Solving

One of the biggest challenges was turning the interface I designed in Project Two into a working application for Project Three. I had to connect multiple components, including the database, inventory controls, and SMS settings, while making sure the app remained easy to use. Another challenge involved troubleshooting the Android emulator when it became slow or stopped responding. Instead of changing multiple things at once, I worked through each issue individually and tested the application after making adjustments. This helped me identify what was causing problems and find solutions without disrupting features that were already working.

Skills and Accomplishments

The component I am most proud of is the database integration and inventory management functionality. Developing the SQLite database and connecting it to the application's interface gave me a better understanding of how mobile applications store, retrieve, and display information. I also gained experience implementing user authentication, handling permissions, and managing interactions between different Android activities. Seeing the application progress from an initial UI design into a functional mobile app was one of the most rewarding parts of the project. Overall, this experience strengthened my Java programming, debugging, and mobile development skills while giving me a project I can showcase in my computer science portfolio.
