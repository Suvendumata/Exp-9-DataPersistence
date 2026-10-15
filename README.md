# Experiment 9: Data Persistence in Android

## 1. Aim

To develop an Android application using Kotlin to demonstrate data persistence and understand how data can be stored and retrieved using SQLite database in Android.

## 2. Introduction

Data persistence is the process of storing data so that it remains available even after an application is closed or the device is restarted. In Android applications, data persistence is important for maintaining user information, login details, and application records.

This experiment demonstrates data persistence using an Android application developed with Kotlin. The application uses SQLite, a lightweight relational database available in Android, to store and retrieve student information.

## 3. Technology Used

- **Android Studio:** IDE used to develop and test the Android application.
- **Kotlin:** Programming language used for application development.
- **SQLite:** Local relational database used to store student records.
- **XML:** Used for designing the user interface, if applicable to the project.
- **Gradle:** Used to manage project configuration and dependencies.
- **Android Emulator / Physical Device:** Used to execute and test the application.

## 4. Scenario

The application demonstrates a student database management scenario. Users can enter student information, add student records, view stored database records, and access the student database through the application interface.

The screenshots included in this repository demonstrate the student data entry screen, login screen, database records, SQLite database, and student database.

## 5. Concepts Used

### Data Persistence

Data persistence allows information to remain stored beyond the current execution of an application.

### SQLite Database

SQLite is a lightweight, embedded relational database that stores structured information locally on an Android device.

### CRUD Operations

CRUD stands for Create, Read, Update, and Delete. These operations are commonly used to manage database records. The operations implemented in this experiment depend on the application's actual functionality.

### Local Database Storage

Local storage allows an application to save and retrieve information without requiring a remote database server.

## 6. Project Folder Structure

The following is the project structure visible in Android Studio:

```text
Exp-9 DataPersistenceDemo/
├── .gradle/
├── .idea/
├── app/
├── gradle/
├── Screenshots/
│   ├── AddStudentData.png
│   ├── DatabaseRecords.png
│   ├── LoginScreen.png
│   ├── SQLiteDatabase.png
│   └── StudentDatabase.png
├── .gitignore
├── build.gradle.kts
├── gradle.properties
├── gradlew
├── gradlew.bat
├── local.properties
├── README.md
└── settings.gradle.kts
```

### Description of Important Files and Folders

- **app/**: Contains the main Android application module, source code, resources, and app-level configuration.
- **gradle/**: Contains Gradle wrapper configuration files.
- **Screenshots/**: Contains screenshots demonstrating the application screens and database output.
- **.gradle/**: Contains Gradle-generated project cache files.
- **.idea/**: Contains Android Studio project settings.
- **build.gradle.kts**: Defines the project-level Gradle build configuration.
- **gradle.properties**: Contains Gradle configuration properties.
- **gradlew**: Gradle wrapper script for Linux and macOS.
- **gradlew.bat**: Gradle wrapper script for Windows.
- **settings.gradle.kts**: Defines the Gradle project and included modules.
- **local.properties**: Contains local SDK configuration; this file should generally not be committed to a public repository.
- **.gitignore**: Specifies files and folders Git should ignore.
- **README.md**: Documents the experiment, its structure, and screenshots.

## 7. Procedure

1. Open Android Studio and create or open the `Exp-9 DataPersistenceDemo` project.
2. Configure the project using Kotlin and Gradle.
3. Design the application screens required for login and student data management.
4. Implement the database functionality using SQLite.
5. Add the required code to insert and retrieve student information.
6. Run the application on an Android emulator or a physical Android device.
7. Enter student details and perform the available database operations.
8. Verify that the student records are stored and displayed correctly.
9. Capture screenshots of the application screens and database output.
10. Store the screenshots in the `Screenshots` folder.
11. Upload the project files and screenshots to GitHub.
12. Document the experiment and test cases in this README file.

## 8. Application Screenshots

The following screenshots are stored in the `Screenshots` folder of this repository.

### 8.1 Login Screen

![Login Screen](Screenshots/LoginScreen.png)

### 8.2 Add Student Data

![Add Student Data](Screenshots/AddStudentData.png)

### 8.3 Student Database

![Student Database](Screenshots/StudentDatabase.png)

### 8.4 Database Records

![Database Records](Screenshots/DatabaseRecords.png)

### 8.5 SQLite Database

![SQLite Database](Screenshots/SQLiteDatabase.png)

## 9. Test Cases

The following test cases can be used to verify the application's functionality. Record the actual result after executing each test.

### Test Case 1: Login Screen

**Objective:** To verify that the login screen is displayed correctly.

**Procedure:**
1. Launch the application.
2. Verify that the login screen appears.
3. Enter the required login information, if applicable.
4. Observe the application's response.

**Expected Result:** The login screen should be displayed correctly and handle the entered information according to the implemented login logic.

**Screenshot:** See [Login Screen](Screenshots/LoginScreen.png).

### Test Case 2: Add Student Data

**Objective:** To verify that student information can be entered and stored.

**Procedure:**
1. Open the student data entry screen.
2. Enter the required student details.
3. Submit the details using the available save or add option.
4. Check whether the record is stored successfully.

**Expected Result:** The application should store valid student information in the database.

**Screenshot:** See [Add Student Data](Screenshots/AddStudentData.png).

### Test Case 3: Retrieve Database Records

**Objective:** To verify that stored student records can be retrieved and displayed.

**Procedure:**
1. Add a student record to the database.
2. Open the database records screen.
3. Check whether the saved record appears.
4. If applicable, close and reopen the application and verify persistence.

**Expected Result:** Previously saved records should be displayed correctly and remain available after the application is closed and reopened, provided the local database has not been cleared.

**Screenshot:** See [Database Records](Screenshots/DatabaseRecords.png).

## 10. Student Details

- **Name:** [Enter Your Full Name]
- **USN:** [Enter Your USN]
- **Experiment Number:** 9
- **Experiment Name:** Data Persistence in Android
- **Platform:** Android Studio
- **Language:** Kotlin
- **Database:** SQLite

**Important:** At least one actual test screenshot must show your name and USN. Capture a screenshot of the application displaying these details and add it to the `Screenshots` folder. Then include it in this README using the following Markdown, replacing the filename with your actual image filename:

```markdown
### Student Details Screenshot

![Student Name and USN](Screenshots/StudentDetails.png)
```

## 11. Result

The Android data persistence experiment demonstrates the use of local database storage for student information. The application screens and database output can be verified using the screenshots included in the repository. The test cases help validate data entry, storage, and retrieval functionality.

## 12. Conclusion

This experiment provides practical knowledge of data persistence in Android application development using Kotlin and SQLite. It demonstrates the importance of local database storage and the process of documenting application functionality, project structure, and test results using GitHub.

## 13. GitHub Repository

Source code, project configuration, README documentation, and application screenshots are maintained in this repository.

**Repository:** https://github.com/Suvendumata/Exp-9-DataPersistence

