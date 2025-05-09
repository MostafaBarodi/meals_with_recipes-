# Meals App

A Flutter app that allows users to view a list of meals and filter them based on various dietary preferences, such as gluten-free, lactose-free, vegetarian, and vegan.

## Features

* **Meal Display**: A list of meals with details such as title, duration, and image.
* **Filtering**: Filters to display meals based on dietary preferences (e.g., gluten-free, vegetarian).
* **State Management**: Managed with Riverpod for reactive updates when filters are applied.

## Screens

* **Home Screen**: Displays a list of meals, filtered by the active filters.
* **Filters Screen**: Allows users to toggle between different dietary filters.

## Folder Structure

```
lib/
├── data/
│   ├── dummy_data.dart       # Contains dummy meal data
│   └── models/
│       └── meal.dart         # Contains the Meal model class
├── providers/
│   └── meals_provider.dart   # Contains Riverpod providers
├── screens/
│   ├── home_screen.dart     # Home screen for displaying meals
│   └── filters_screen.dart  # Filter screen to manage meal filters
├── widgets/
│   ├── meal_item.dart       # Widget to display individual meal
│   └── filter_switch.dart   # Widget for a filter switch
└── main.dart                # Main entry point of the app
```

## Installation

Follow these steps to run the app on your local machine:

### 1. Clone the repository

```bash
git clone https://github.com/MostafaBarodi/meal_app.git
cd meal_app
```

### 2. Install Dependencies

Make sure you have Flutter installed on your system. If you haven't, follow the installation guide on the [official Flutter website](https://flutter.dev/docs/get-started/install).

Run the following command to install the necessary dependencies:

```bash
flutter pub get
```

### 3. Run the app

Now, you can run the app on an emulator or a physical device:

```bash
flutter run
```

The app should now be running on your device or emulator.

## Usage

1. **Home Screen**: You'll see a list of meals displayed. You can tap on a meal to see more details.
2. **Filters Screen**: Navigate to the filters screen to toggle between different dietary filters, such as:

   * Gluten-Free
   * Lactose-Free
   * Vegetarian
   * Vegan

   The meals list will automatically update based on the active filters.

## State Management

* **Riverpod** is used for state management:

  * `filtersProvider`: Manages the state of the selected filters.
  * `filteredMealsProvider`: Filters meals based on the active filters.

## Dependencies

* `flutter_riverpod`: State management for Flutter.
* `flutter`: The main SDK for building the app.

You can find all the dependencies in the `pubspec.yaml` file.

## Contributing

1. Fork the repository.
2. Create a new branch for your feature or bugfix (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Screenshots

Here are some screenshots of the app:

![Home Screen](assets/images/screenshot1.png)
![Meals List](assets/images/screenshot2.png)
![Recipe Detail](assets/images/screenshot3.png)
![Favorit a meal](assets/images/screenshot4.png)
![Favorit List](assets/images/screenshot5.png)

