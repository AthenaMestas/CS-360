# CS-360
Project Overview

For CS-360 Mobile Architecture and Programming, I developed an Android weight-tracking application designed to help users record their weight, set personal goals, and monitor their progress over time. 

1. What user needs was this app designed to address?

The application was designed for users who want a convenient way to monitor changes in their weight and track progress toward a personal goal. 
2. What screens and features were necessary to support user needs?

The app includes screens for logging in or creating an account, viewing weight records, adding weight entries, and managing SMS permissions. I focused on keeping the layout consistent, with clearly labeled buttons, organized information, and simple navigation. I also made SMS notifications optional so users can continue using the application without granting additional permissions.

3. How did you approach coding your app? What techniques or strategies did you use?

I approached development by breaking the application into smaller components and implementing each feature individually. I started with the UI layouts in Android Studio before connecting them to the application's Java code and SQLite database. Testing features as I developed them also made troubleshooting more manageable. 

4. How did you test to ensure your code was functional?

I tested the application using an Android Studio emulator and checked important functions such as account creation, login, saving and managing weight entries, and tracking progress toward a goal. Testing was important because it helped verify that the screens, database, and underlying code worked together as intended. It also reinforced the importance of checking different user interactions rather than assuming a feature works because the code runs.

5. Where did you have to innovate to overcome a challenge?

One challenge was moving from a UI design with sample information to an application that could store and display actual user data. This required connecting the weight records screen to SQLite and ensuring the displayed entries and goal progress reflected changes in the database. Another important consideration was handling SMS permissions without making notifications a requirement for using the app.

6. In what component were you particularly successful in demonstrating your skills?

I am particularly proud of the weight records feature because it combines several important development concepts. Users can add, view, update, and delete weight entries, with the information saved in the SQLite database. 
