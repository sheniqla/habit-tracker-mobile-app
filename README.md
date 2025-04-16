
<!---
============================================================================
                  CURSOR AI INSTRUCTIONS - DO NOT MODIFY
============================================================================
-->

<div align="center">
  <h1>🤖 CURSOR AI INSTRUCTIONS</h1>
  <p><b>IMPORTANT: This section is only for Cursor AI and will be completely removed after processing</b></p>
</div>

---

## AI Task: Complete README Transformation

Hello Cursor AI! Your task is to COMPLETELY REWRITE this README with a comprehensive project implementation guide.

### Critical Requirements:

1. **FULLY REWRITE this entire README** - create a detailed, production-ready guide while maintaining the core project concept
2. **Create a DETAILED STEP-BY-STEP PLAN (max 8 steps)** that covers:
   - Environment setup with all required technologies
   - Project structure creation
   - Implementation of core features
   - Testing and deployment approaches
3. **Tailor content to the user's profile:**
   - User's Experience Level: `Beginner`
   - User's Available Time: `A Few Days`
4. **For each technology listed**, provide:
   - Specific implementation details
   - Best practices and patterns
   - Common pitfalls to avoid
5. **Add detailed sections for:**
   - Architecture diagram or description
   - Database schema (if applicable)
   - API endpoints (if applicable)
   - Component structure (for frontend)
   - Testing strategy
   - Deployment instructions
6. **Provide code examples** for critical project parts
7. **REMOVE THESE INSTRUCTIONS COMPLETELY** after your rewrite

Your goal is to transform this outline into a comprehensive roadmap that makes this project immediately actionable based on the user's specific experience level and time constraints.

### ⚠️ CRITICAL FIRST STEP ⚠️

**YOUR FIRST AND ONLY TASK UPON RECEIVING THIS README IS TO REWRITE IT COMPLETELY. DO NOT START IMPLEMENTING THE PROJECT OR WRITING ANY CODE YET.**

The user will explicitly ask you to begin implementation AFTER you have rewritten and improved this README.

<!---
============================================================================
                 END OF CURSOR AI INSTRUCTIONS
============================================================================
-->


# Habit Tracker Mobile App

## Project Overview
A mobile app to track and manage personal goals and habits, allowing users to set and achieve their objectives.


> **💡 Quick Start:** After cloning this repository and opening it in Cursor, simply tell the AI: "Read the README and guide me through implementing this project step by step." Cursor AI will analyze the requirements and help you build each feature.


## User Profile
- **Experience Level:** Beginner
- **Available Time to Complete:** A Few Days

## Technologies
- **React Native**: Used to build the mobile app's user interface and functionality.
- **JavaScript**: Used as the programming language for the app's logic and interactions.
- **AsyncStorage**: Used to store and retrieve user data locally on the mobile device.
- **Redux**: Used to manage the app's state and handle user interactions efficiently.
- **Expo**: Used to simplify the development process and provide a set of pre-built components for the app.


## Development Steps
### 1. Setup the Development Environment
Install Node.js, Expo CLI, and set up a new React Native project.

### 2. Design the User Interface
Create the app's layout, design the habit tracking feature, and implement basic navigation.

### 3. Implement Habit Tracking Feature
Develop the habit tracking feature, allowing users to add, edit, and delete habits.

### 4. Implement Data Storage using AsyncStorage
Store and retrieve user habit data locally on the mobile device using AsyncStorage.

### 5. Implement State Management using Redux
Manage the app's state and handle user interactions efficiently using Redux.

### 6. Test and Debug the App
Test the app's functionality, identify and fix bugs, and ensure a smooth user experience.

### 7. Publish the App
Publish the app to the app stores (e.g., Apple App Store, Google Play Store) for users to download and use.


## Main Features
Features will be added soon


## Sample Code
```javascript
// Example code snippet for habit tracking feature
function addHabit(habit) {
  AsyncStorage.setItem('habits', habit);
  console.log('Habit added successfully');
}
```


## Getting Started
Instructions will be added soon

## Resources
- [React Native Documentation](https://reactnative.dev/docs/getting-started) (documentation)
- [Expo Documentation](https://docs.expo.dev/) (documentation)
- [Redux Tutorial](https://redux.js.org/tutorials/essentials/part-1-overview) (tutorial)
- [AsyncStorage Documentation](https://react-native-async-storage.github.io/async-storage/docs/usage) (documentation)
- [React Native Tutorial for Beginners](https://www.youtube.com/watch?v=0-S5a0eXPoc) (video)


## AI Coding Prompts

Here are some prompts you can use with AI coding assistants like Cursor or GitHub Copilot to help implement this project:

### Prompt 1
```
Create a new React Native project using Expo and set up the basic file structure. Then, generate a starter code for the Habit Tracker app's main screen, including a text input field and a button to add habits. Use React Native's built-in components and Expo's pre-built components to simplify the process.
```

### Prompt 2
```
Implement the core functionality of the Habit Tracker app by writing a function to handle the 'addHabit' action. This function should use Redux to dispatch an action to update the app's state and then store the new habit in AsyncStorage. Make sure to handle any potential errors that may occur during data storage.
```

### Prompt 3
```
Enhance the Habit Tracker app by adding a feature to display a list of user's habits. Use Redux's connect function to connect the habit list component to the app's state and then use AsyncStorage to retrieve the stored habits and render them in the list. You can also add a delete habit functionality and handle any edge cases that may arise.
```


Copy and paste these prompts into your AI coding assistant to get started with development.


---
*Generated by [CodeSpark](https://github.com/YOUR_USERNAME/codespark)*
