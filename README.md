# Setup process and any challenges faced in Mobile Development Environment

## Steps to Install Expo Go

0. Setting Up and Testing Your Mobile Development Environment Objective

Mobile development demands more computational resources compared to web development. To ensure a smooth development experience, we will be using the Expo Framework for React Native, which simplifies mobile app development and testing.

1. Visit the official Expo Go homepage: https://expo.dev/go.
2. Select the latest SDK version.
3. Click on Install for your device:
4. Android: Install from the Google Play Store.
iOS: Install from the Apple App Store.
5. Open the Expo Go app on your device.
6. Create a new account or log in if you already have one.

## Create Your First Mobile App

1. Create Your First Mobile App

Set up your first mobile application using the Expo Router template. Document the scaffolding process and understand the file structure of a React Native application using Expo.

Document what happens when you reset the project

1. I placed the command npm run reset-project in the terminal
2. appeared a question Do you want to move existing files to /app-example instead of deleting them? (Y/n)
3. when answering yes, it moves them to the exsmble app folder and deletes unnecessary files.
4. I answered no because I do not want to transfer the files again, I want to delete them permanently
5. did these things 
    1. ❌ /app deleted.
    2. ❌ /components deleted.
    3. ❌ /hooks deleted.
    4. ❌ /constants deleted.
    5. ❌ /scripts deleted.

    6. 📁 New /app directory created.
    7. 📄 app/index.tsx created.
    8. 📄 app/_layout.tsx created.

deleted many unused files and also removed all items from the main page.

## 2. Implementing Mobile Components in React Native

React Native Components and Styling

In React Native, you work with predefined components that translate directly into native components on iOS and Android. These components act as the building blocks of your application, much like HTML elements (such as <div> and <p>) in web development.

For example: - Instead of <div> in web development, you use <View> in React Native. - Instead of <p> for text content, you use <Text>.

By leveraging these predefined components, React Native ensures that your app maintains the native look and feel on both platforms while keeping development efficient.


## 3. Implementing Safe Areas, Images, and Touchable Components in React Native

In this task, you will explore essential React Native components like SafeAreaView, Image, ImageBackground, TouchableOpacity, and Dimensions. These components are crucial for building visually appealing and responsive applications.

## 4. Explore More Core Components

React Native provides developers with a set of predefined components that render natively on both iOS and Android. You can find more details here: React Native Components

To gain hands-on experience, you will build a sample app that implements some of these core components. This exercise will help reinforce your understanding and improve your coding efficiency.

Note: Avoid copying and pasting code. Instead, type each line manually to enhance retention and familiarity with the syntax.

