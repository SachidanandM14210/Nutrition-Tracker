# Nutrition Tracker

Nutrition Tracker is a Java desktop GUI application designed for Indian students to track their nutritional intake in a simple and practical way. This application allows users to easily add, view, and manage their nutritional data, helping them maintain a balanced diet.

## Features

- User-friendly interface for tracking nutritional intake.
- Ability to add nutritional values such as calories, protein, and carbohydrates.
- View and manage previously entered nutritional data.
- Simple and intuitive design tailored for students.

## Project Structure

```
nutrition-tracker
├── src
│   ├── main
│   │   ├── App.java
│   │   ├── gui
│   │   │   ├── MainFrame.java
│   │   │   ├── AddNutritionDialog.java
│   │   │   └── ViewNutritionPanel.java
│   │   ├── models
│   │   │   └── Nutrition.java
│   │   ├── services
│   │   │   └── NutritionService.java
│   │   └── utils
│   │       └── Constants.java
│   └── test
│       └── NutritionServiceTest.java
├── lib
├── README.md
└── build.gradle
```

## Setup Instructions

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```
   cd nutrition-tracker
   ```

3. Build the project using Gradle:
   ```
   ./gradlew build
   ```

4. Run the application:
   ```
   java -jar build/libs/nutrition-tracker.jar
   ```

## Usage Guidelines

- Launch the application to access the main interface.
- Use the "Add Nutrition" dialog to input your nutritional values.
- View your tracked nutritional data in the main panel.
- Ensure to save your entries for future reference.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.