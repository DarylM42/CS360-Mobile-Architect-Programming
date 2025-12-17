# CS360-Mobile-Architect-Programming

CS‑360 Module Eight Journal Reflection
Summary of Requirements and Goals The Event Tracking App was developed to provide users with a reliable way to manage personal and professional events. The requirements included user authentication, event creation and editing, persistent storage using Room, a grid‑based display of events, and SMS notification functionality. The app was designed to address user needs for simple event management and timely reminders.

Screens and Features The app includes a login and registration screen, an event grid screen with add, edit, and delete functionality, and an SMS screen for sending reminders. These screens were necessary to support user needs and create a user‑centered interface. The UI designs kept users in mind by emphasizing clarity, straightforward navigation, and immediate feedback through Toast messages. The designs were successful because they balanced simplicity with functionality, ensuring that users could accomplish tasks without confusion.

Coding Approach I approached coding by breaking the project into milestones: authentication, event CRUD operations, RecyclerView integration, and SMS functionality. I used strategies such as modularizing code, verifying XML IDs against Java references, and testing each feature incrementally. These techniques can be applied in future projects to maintain clarity, reproducibility, and systematic debugging.

Testing Process Testing was conducted on both emulators and physical devices. I verified login and registration, event creation and deletion, and SMS sending. This process was important because it confirmed that the app worked as intended and revealed issues such as missing XML IDs and runtime permission handling. Addressing these issues improved the stability and usability of the app.

Innovation and Challenges One challenge was restoring SMS functionality after it initially disappeared from the app. I overcame this by re‑adding the navigation button in the event grid layout and wiring it to SmsActivity. Another challenge was handling Room schema warnings, which I resolved by adjusting configuration. These innovations ensured the app met rubric requirements and functioned reliably.

Successes I was particularly successful in demonstrating my knowledge of Room persistence and RecyclerView integration. The event grid displays data efficiently, updates dynamically after edits or deletions, and persists across sessions. This component showcases my ability to combine database management with user interface design in a way that supports user needs.
