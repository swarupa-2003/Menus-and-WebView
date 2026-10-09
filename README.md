# Experiment 8: Implement Menus and WebView in an Android Application

## Student Details

* **Name:** SWARUPA S
* **USN:** 25MCAR0137
* **Experiment No.:** 8
* **Title:** Implement Menus and WebView in an Android Application
* **Technology:** Android Studio, Kotlin, XML

---

## 1. Aim

To develop an Android application that implements menus for navigation and uses a WebView to display web content within the application.

## 2. Objective

* To understand menu implementation in Android.
* To create and handle menu items.
* To implement WebView for displaying web pages.
* To understand event handling and user interaction.
* To test menu navigation and WebView functionality.

## 3. Concept and Technology

### Menus in Android

Menus provide users with options to perform actions or navigate through an application. Android supports different types of menus, including:

* **Options Menu:** Displays actions in the app bar or overflow menu.
* **Context Menu:** Displays actions related to a selected view.
* **Popup Menu:** Displays a small menu anchored to a particular view.

In this experiment, an options menu is used to provide navigation and actions.

### WebView

WebView is an Android component that allows web content to be displayed inside an application without opening a separate browser.

Important components include:

* `WebView`: Displays web pages.
* `WebViewClient`: Helps load web pages inside the application.
* `INTERNET` permission: Allows the application to access online web content.
* `loadUrl()`: Loads a specified URL in the WebView.

## 4. Scenario

The application represents a simple web browser inside an Android app. Users can open a web page, navigate using menu options, and access a home page through the options menu.

The application demonstrates how menus and WebView can be combined to improve navigation and usability.

## 5. Features

* Options menu with multiple items.
* Web pages displayed inside the application.
* Home page navigation.
* Menu item selection and event handling.
* Simple and user-friendly interface.

## 6. Folder and File Structure

```text
Experiment8/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com/example/experiment8/
│   │   │   │       └── MainActivity.kt
│   │   │   ├── res/
│   │   │   │   ├── layout/
│   │   │   │   │   └── activity_main.xml
│   │   │   │   ├── menu/
│   │   │   │   │   └── main_menu.xml
│   │   │   │   └── values/
│   │   │   │       ├── strings.xml
│   │   │   │       └── themes.xml
│   │   │   └── AndroidManifest.xml
│   └── build.gradle.kts
├── screenshot.png
├── test-screenshots/
│   ├── test-case-1.png
│   ├── test-case-2.png
│   └── test-case-3.png
├── build.gradle.kts
├── settings.gradle.kts
└── README.md
```

*Note: The structure may vary depending on the Android Studio project template. Include only files and folders that exist in your project.*

## 7. Implementation Overview

### MainActivity.kt

The main activity initializes the WebView, loads the initial web page, creates the options menu, and handles menu item selections.

### activity_main.xml

Defines the user interface containing the WebView.

### main_menu.xml

Defines the menu items used for navigation, such as Home, Google, and Refresh.

### AndroidManifest.xml

Declares the application components and the internet permission required to load online web pages.

Example permission:

```xml
<uses-permission android:name="android.permission.INTERNET" />
```

## 8. Output Screenshot

Add a screenshot of your running Android application below.

![Application Output](screenshot.png)

**Screenshot requirements:**

* Show the application running in the emulator.
* Display the loaded web page.
* Capture the options menu in a separate screenshot if possible.

## 9. Test Cases

### Test Case 1: Verify Options Menu

**Objective:** To verify that the options menu displays the available menu items.

**Steps:**

1. Launch the application.
2. Open the options menu.
3. Verify that the menu items are visible.

**Expected Result:** The options menu opens and displays the available actions.

**Actual Result:** Record the result after testing.

![Test Case 1 - Options Menu](test-screenshots/test-case-1.png)

### Test Case 2: Verify WebView Loading

**Objective:** To verify that a web page loads inside the application.

**Steps:**

1. Launch the application.
2. Select the Google menu item.
3. Wait for the web page to load.

**Expected Result:** The Google website opens inside the WebView without launching an external browser.

**Actual Result:** Record the result after testing.

<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/a9430cf7-ae42-4569-91f0-c89714b21ab5" />


### Test Case 3: Verify Student Details and Navigation

**Objective:** To verify the application functionality and display the student's identification details for submission.

**Student Name:** SWARUPA S

**USN:** 25MCAR0137

**Steps:**

1. Launch the application.
2. Display your name and USN in the application interface or a dedicated student-details screen.
3. Use the menu to navigate to the home page.
4. Capture a screenshot showing your name and USN.

**Expected Result:** The student details are displayed correctly, and menu navigation works as expected.

**Actual Result:** Record the result after testing.

![Test Case 3 - Student Details](test-screenshots/test-case-3.png)

> **Important:** Add genuine screenshots from your own emulator. For Test Case 3, make sure your name and USN are visibly displayed in the application itself.

## 10. Result

The Android application was developed to demonstrate menu implementation and WebView integration. The application can display web content internally and provide navigation through menu options.

The test cases should be executed and their actual results recorded before submission.

## 11. Conclusion

This experiment demonstrates how menus can be implemented to provide navigation and actions in an Android application. It also explains how WebView can be used to display web pages inside the application, improving integration between Android interfaces and web content.

## 12. GitHub Submission

Upload the Android Studio project, README.md, output screenshot, and all three test-case screenshots to your GitHub repository.

**Repository:** Add your GitHub repository URL here.
