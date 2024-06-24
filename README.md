# GrocerVision Mobile Application

## Summary

The **GrocerVision Mobile Application** is a comprehensive solution designed to enhance the grocery shopping experience for customers while providing robust management tools for administrators. The mobile app allows customers to:

- Browse products
- Manage their shopping carts
- Checkout order
- Create and maintain wishlists
- View their order history

## IDE

**Name and version of the IDE:**
Android Studio Giraffe | 2022.3.1 Patch 3

## APIs and Third-Party Libraries

1. **Firebase**

   - **Authentication:** For user authentication (sign up, login, forget password)
   - **Firestore:** For database management of products and orders
   - **Storage:** For storing product images

2. **Provider**

   - For state management in Flutter applications

3. **Flutter Icons (Iconly)**

   - For using a variety of icons throughout the application

4. **Fancy Shimmer Image**

   - For displaying shimmer effect images while loading

5. **Fluttertoast**

   - For displaying toast messages

## Additional Steps to Run the Program

1. **Clone the Repository**

   ```sh
   git clone <repository_url>
   ```

2. **Set Up Firebase**

- Create a Firebase Project:

  1. Go to the Firebase Console
  2. Click on "Add project" and follow the setup instructions

- Register Your App with Firebase:

  1. In the Firebase Console, click on "Add app" and select the Android icon
  2. Follow the steps to register your app with Firebase
  3. Download the google-services.json file
  4. Place the google-services.json file in the android/app directory of your Flutter project

- Add Firebase SDK:
  1. Open the android/build.gradle file and add the following line to the dependencies section:
  ```sh
   classpath 'com.google.gms:google-services:4.3.10'
  ```
  2.  Open the android/app/build.gradle file and add the following line at the bottom of the file:
  ```sh
  apply plugin: 'com.google.gms.google-services'
  ```
  3.  Install Dependencies
  ```sh
  flutter pub get
  ```
  4.  Run the App
  - Open the project in Android Studio
  - Select the device (e.g., Pixel 7 Pro API 34) from the device dropdown
  - Click on the 'Run' button or run:
  ```sh
  flutter run
  ```
