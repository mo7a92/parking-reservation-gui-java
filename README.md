# 🅿️ Parking Reservation System (Java GUI)

An interactive desktop application built with Java Swing that allows users to reserve and cancel parking slots with a visual interface. It includes slot status tracking and persistent file-based saving.

## 🧠 Key Features
- Click to reserve or cancel parking slots  
- Red = Reserved, default = Available  
- Reservation data saved and loaded from file  
- Feedback messages shown in the UI  
- Includes visual icon for branding (`parking.png`)

## 🧰 Technologies Used
- Java  
- Swing (GUI toolkit)  
- File I/O  
- Custom icon (`parking.png`)

## 📁 Image Setup (IMPORTANT ⚠️)
This project **uses an image called `parking.png` for the UI**. You must manually create the following folders if they don’t exist:

```
src/
└── resources/
    └── images/
        └── parking.png   ← place the image here
```

> 💡 **Note:** Java does not create this folder structure by default.  
> You must create the `resources/images/` path yourself, and place `parking.png` inside it.

If the image is missing or placed elsewhere, the program won’t show the parking icon correctly.

## ▶️ How to Run
1. Open the project in NetBeans, IntelliJ, or any Java IDE  
2. Set the `Main.java` file as the main class  
3. Ensure `parking.png` is placed in `src/resources/images/`  
4. Run the app — the GUI will appear with slot buttons and icon

## 💾 Data Saving
- Reserved slots are saved to a file (e.g., `reservations.txt`)
- Slot status is restored automatically when the app runs again


