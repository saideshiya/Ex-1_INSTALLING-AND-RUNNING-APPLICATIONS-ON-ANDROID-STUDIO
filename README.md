# EX-1: INSTALLING AND RUNNING APPLICATIONS ON ANDROID STUDIO

**Name:** SAI DESHIYA K

**Register Number:** 21224220084

## Aim

To develop and run a simple Temperature Converter application using Android Studio, Java, and XML to convert temperature from Celsius to Fahrenheit.

## Software Requirements

- Android Studio
- Java Development Kit (JDK)
- Android SDK
- Android Virtual Device (AVD)
- Java
- XML

---

## Step 1 – System Requirements

The required software tools are used to develop, design, and run Android applications. Android Studio provides the development environment, Java is used to implement the application functionality, and XML is used to design the user interface.

### Required Software

- Android Studio
- Java Development Kit (JDK)
- Android SDK
- Android Emulator

---

## Step 2 – Setup Android Studio

Android Studio is the official Integrated Development Environment (IDE) used for Android application development.

### Installation Procedure

1. Download Android Studio from the official website.
2. Run the installer and follow the installation instructions.
3. Install the required Android SDK components.
4. Configure the Android SDK location.
5. Set up an Android Virtual Device if required.
6. Launch Android Studio.
7. Create a new project using the Empty Views Activity template.
8. Select Java as the programming language.

---

## Creating the Temperature Converter Application

1. Open the project in Android Studio.
2. Design the user interface using the `activity_main.xml` file.
3. Add a heading named **Temperature Converter**.
4. Add an EditText field to enter the temperature in Celsius.
5. Add a Button named **Convert**.
6. Add a TextView to display the converted temperature.
7. Open the `MainActivity.java` file.
8. Initialize the EditText, Button, and TextView using `findViewById()`.
9. Implement the button click event using `setOnClickListener()`.
10. Read the temperature entered by the user.
11. Convert Celsius to Fahrenheit using the formula:

   **Fahrenheit = (Celsius × 9/5) + 32**

12. Display the converted temperature in the TextView.

---

## Step 3 – Create Android Virtual Device (AVD)

An Android Virtual Device is used to test and run the application without requiring a physical Android phone.

### Procedure

1. Open Device Manager in Android Studio.
2. Click **Create Virtual Device**.
3. Select a suitable device configuration.
4. Select and download an Android system image if required.
5. Finish the configuration and start the emulator.
6. Select the emulator from the device dropdown menu.

---

## Step 4 – Run the Application

1. Open the Temperature Converter project.
2. Select the configured Android Emulator.
3. Click the **Run ▶** button in Android Studio.
4. Wait for the application to build and launch.
5. Verify that the Temperature Converter screen appears.
6. Enter a temperature value in Celsius.
7. Click the **Convert** button.
8. Verify that the corresponding Fahrenheit value is displayed.

---

## Output

The application displays the heading **Temperature Converter**, an input field to enter the Celsius value, a Convert button, and a text field to display the result.

For example, when the user enters **37°C** and clicks the Convert button, the application displays:

**Fahrenheit: 98.60 °F**

<img width="1735" height="1070" alt="image" src="https://github.com/user-attachments/assets/489a8d79-68a6-46b1-ad7f-2fd7a7dcd396" />


---

## Result

Thus, the Temperature Converter application was successfully developed and executed using Android Studio. The application converts temperature from Celsius to Fahrenheit and displays the result when the Convert button is clicked.
