| Outline        |                               |
| -------------- | ----------------------------- |
| Course         | SEG 4105                      |
| Material       | Tut 5                         |
| Student        | Khai Tran                     |
| Student Number | 300112587 ktran093@uottawa.ca |

## Workout Generation - Andy

- **Objective:** Develop a survey feature that tailors a workout routine based on user input.
- **Key Features:**
  1. Closed-type survey questions.
  2. Ability to undo or restart the survey.
  3. Saving and utilizing workout routine within the app.
  4. User-friendly interface.

**Problem Statement:** Overwhelming choices of exercises lead to decision paralysis. A predefined list simplifies the process of starting a fitness journey.

- **Appetite:** 6 weeks for development.
  - Survey should be closed-type.
  - Questions should avoid any personal inquiries.
  - Must fit within the existing "FitShare" framework.
- **Solution Proposal:**
  1. Use closed questions to tailor workouts.
  2. Allow users to modify their answers.
  3. Translate survey answers into tangible metrics to generate a workout routine.
  4. Ensure accessibility and understandability of the survey's UI.
- **Potential Challenges (Rabbit Holes):**
  1. Ensure no data from the survey is stored post-generation.
  2. Ensure clarity in questions to avoid misinterpretations.
  3. Prevent bias in survey questions.
- **Boundaries (No Go's):**
  1. The feature should not consider past workouts or goals.
  2. Avoid any personal questions.

**Question: How does this feature align with our overall value proposition for FitShare?**

**Andy's Answer: FitShare main goal is to allow kind of user to start working out and sharing their own workouts. This feature would simplify the process of creating a workout from a set of exercises by allowing any kind of individual to answer a few simple questions and get a workout tailored to their preferences immediately. This follows one of the main value propositions for FitShare of having a feature that supports another means of creating workouts for users using the application.**

## Social Interaction - Luka

- **Objective:** Enhance user engagement by introducing social interaction, allowing users to share, follow, and adopt each other's workout routines.
- **Key Features:**

  1. Follow and unfollow other users.
  2. Visibility settings for workouts and routines.
  3. Adopt friends' workouts into personal account.

- **Problem Statement:** Regular activity is challenging for many due to a lack of motivation, knowledge, and accountability. It's also a hurdle to invest resources in learning the basics of exercise.

- **Appetite:** 4 weeks.

  - The feature should provide easy search functionality.
  - Users should be able to view their followers and those they are following.
  - Integration required for both frontend and backend of the FitShare application.

- **Solution Proposal:**

  1. Search functionality to find and follow friends.
  2. One-click to follow users with public profiles.
  3. Access to visible workouts and routines of friends.
  4. Option to save friends' routines and workouts.
  5. Dedicated page to view followers and following.

- **Potential Challenges (Rabbit Holes):**

  1. Ensuring search functionality is optimized - not too strict or too loose.
  2. Avoiding complexities in backend logic related to following mechanics.

- **Boundaries (No Go's):**
  1. Incorrect search results.
  2. Bugs or issues with the following mechanism.

## History - Adhish

**Objective:**

- Provide an intuitive and insightful interface for users to view and interact with their past workout history, enhancing user engagement and loyalty.

**Key Features:**

- Calendar widget for intuitive date selection and display.
- Navigation to detailed session history.
- Display of weekly workouts within the calendar interface.
- List views of prior workouts, with stats such as calories burned.

**Problem Statement:**

- Users currently lack the capability to access or easily view their workout history, which creates a hole in functionality and diminishes user incentive. The feature's ideal location is on the homepage to promote regular interaction.

**Appetite:**

- 2 weeks, with a small team of developers.
  - Dependencies: Completion of "sessions" and "workout history" features.
  - Requirements span design (for the widget and flow), front-end, and back-end (data storage and API calls).

**Solution Proposal:**

- Implement a calendar widget as the primary interface.
- Allow users to select specific dates to view associated workouts.
- Direct navigation to a broader session history.
- Showcase the week's workouts directly within the calendar interface.

**Potential Challenges (Rabbit Holes):**

- CSV conversion: Providing users with the ability to export their workout data into CSV. This feature introduces backend complexity and needs to be balanced with core functionalities.

**Boundaries (No Go's):**

- Avoid data integration attempts from external platforms, especially Apple Health Kit, given the web-based nature of FitShare.

## Login and Signup Feature - Ava

**Breadboarding:**

- **Stage 1:** [Image Placeholder]
- **Stage 2 (Refined):** [Image Placeholder]

**Objective:**

- Enable user personalization by introducing a login and signup feature, allowing for creation, access, and sharing of tailored workouts and routines.

**Key Features:**

- Simple login with username and password.
- Minimalistic signup requiring essential fields.
- User authentication and error handling.
- Ability for users to add friends.
- Capability for users to save and recall their workout routines.

**Problem Statement:**

- Potential users face challenges in finding and crafting workouts suited to their needs. By allowing personalized user accounts, users can both refer to more seasoned gym-goers and share their workouts, thus creating a supportive community.

**Appetite:**

- 6 weeks.
  - Login should be simplified with just username and password.
  - Signup should be streamlined with minimal input fields.

**Solution Proposal:**

- The login and signup interfaces should remain clean and straightforward with fields for user data input.
- Post data entry, the system should authenticate users and provide error feedback if present.
- Upon successful account creation, users should be able to connect with friends and store their specific workouts and routines.

**Potential Challenges (Rabbit Holes):**

- Steering clear from overcomplicating the signup process by demanding additional user details. Focus on name, email, and password for account creation.

**Boundaries (No Go's):**

- For the current scope, the login feature should not consider Two-Factor Authentication (2FA).
