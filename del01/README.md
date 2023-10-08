| Outline        |                               |
| -------------- | ----------------------------- |
| Course         | SEG 4105                      |
| Material       | Lab 3                         |
| Student        | Khai Tran                     |
| Student Number | 300112587 ktran093@uottawa.ca |

# Feature - Sessions

This feature allows users to actively engage with their workouts, track their progress in real-time, and have a seamless experience while transitioning between exercises. It shows the elapsed time of their workout and what exercises are coming up along with details of the exercise.

## Shaping Work

### Problem

While users have access to customized workout playlists and can share or import workouts, there's a gap in real-time engagement. Users lack a centralized interface to interact with their ongoing workouts, making it challenging to monitor their progress, understand the specifics of upcoming exercises, and gauge the elapsed time. This absence diminishes the immersive experience of the workout and can lead to reduced motivation and consistency.

### Appetite

Given the complexity of the feature and the importance of user experience, we're looking at a 6-week cycle to design, develop, test, and deploy the Session feature. This feature ties into the existing `FitShare` logic.

### Solution

**Active Session Interface** - a dedicated page where users will start their workout. This screen displays current and upcoming exercises as well as the duration of the workout.

1. real-time tracking - users can mark completed exercises as they're proressing

2. pause / resume functionality

3. workout summary - summary of the workout once the session is completed

4. history - viewing previously completed sessions

### Rabit Holes

##### Data Storage and Removal

efficiently storing active session data and retrieving it if the user accidentally refreshes or exits the page

### No Go's

1. Real Time Sharing - no integration of real-time sharing or viewing of active sessions

2. advanced analytics - health data is not tracked
