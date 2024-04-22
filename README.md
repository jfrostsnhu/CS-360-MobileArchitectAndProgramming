**CS 360 - Inventory Manager Application Project Readme**

The "Inventory Manager" app was designed to facilitate efficient management of warehouse inventory by providing real-time updates on stock levels, enabling quick addition and removal of items, differing user roles, and requesting SMS permissions for real-time notifications. This app aimed to address the needs of warehouse operations teams and managers by allowing them to maintain accurate stock records, minimize the risk of stock outages, and optimize inventory management processes.

The app features several screens necessary for the facilitation of their use cases such as a login and registration screen, an inventory listing screen, and a screen to view and modify user roles. My designs are successful due to my user-friendlieness and intuitive flow. 

The development of the app involved a structured approach starting with defining the scope, planning the features, and then moving into coding. I used Android Studio for development, focusing on implementing MVC architecture to separate the app's logic from the UI. For database interactions, asynchronous tasks were utilized to ensure the UI remains responsive. These techniques will be beneficial in future projects for maintaining clean code and enhancing app performance.

Testing of my app was conducted using the Android Emulator, supplemented by unit tests for critical functionalities. This process was crucial to ensure that each component of the app functioned as expected. Testing helped identify bugs in the login mechanism and discrepancies in inventory updates and notification generation, which were promptly addressed.

One of the significant challenges was integrating real-time notifications for low stock alerts and a 'mark as read' mechanism. This required use of Android’s Notification API and NotificationManager to handle alerts effectively when inventory levels fell below a set threshold. Additionally, handling multiple screen sizes and orientations without losing UI integrity required creative solutions in responsive design.

A particular success in this project was the seamless integration of the inventory management system with the backend database, allowing for real-time updates and interactions. This component not only showcased my ability to implement complex functionalities but also my skills in designing a user-friendly interface that could handle a dynamic dataset efficiently.

By reflecting on this project, I've gained valuable insights into the practical aspects of app development from initial concept to final implementation. This experience has significantly enhanced my skills in Android development, UI/UX design, and project management.
