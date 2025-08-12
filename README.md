# Safe Gas

Safe Gas is an Android application built using Java in Android Studio as a university capstone project. It aims to enhance the safety of gas cylinder and gas line users, especially in kitchens, by integrating smart sensors and automation.

## Project Overview

Safe Gas provides real-time monitoring of gas leakage, fire, and smoke through strategically placed sensors (smog, fire, and gas detectors) in the kitchen. When a hazard is detected, the system automatically shuts off the gas supply via a device attached to the gas regulator or line and sends instant alerts and notifications to the user’s mobile application.

The application is designed to distinguish between regular cooking smoke/fire and actual emergencies, reducing false alarms.

## Key Features

- **User Authentication:** Sign-up, Login, and Forget Password pages with persistent login using local storage (user remains logged in until uninstall or device reset).
- **Dashboard:** After login, users are greeted with a dashboard where they can add and manage gas cylinders.
- **Cylinder Management:** Users can add cylinders with custom names and details (e.g., "Home Cylinder"). Cylinder information is stored in Firebase.
- **Cylinder Control:** Each cylinder entry displays its name, on/off status, remaining gas percentage, estimated days left, and usage history.
- **Emergency Features:** Quick access to emergency contact numbers for immediate calls.
- **Safety Automation:** Automatic gas shut-off and alert notifications in case of detected hazards.
- **History & Usage Tracking:** Overview of gas usage history and predictions for refills.
- **False Alarm Prevention:** Intelligent detection to avoid alerts triggered by regular cooking smoke or fire.

## Technologies Used

- **Android Studio (Java)**
- **Firebase (Database and Authentication)**
- **Hardware Integration:** Sensor devices for smog, fire, and gas detection; automated gas regulator control.

## How It Works

1. Sensors monitor the kitchen environment for smoke, fire, and gas.
2. On hazard detection, the system:
   - Cuts off gas supply using the regulator device.
   - Sends an alert/notification to the mobile application.
3. Users manage and monitor cylinders through the app, including checking gas levels and usage history.
4. Emergency contacts are available for immediate assistance.

## Use Case

Safe Gas is ideal for households, restaurants, and any environment where gas is used for cooking, providing peace of mind and automated safety.

---

**Note:** This project was developed as a final year capstone in university and demonstrates integration of IoT hardware with a mobile application for real-world safety solutions.
