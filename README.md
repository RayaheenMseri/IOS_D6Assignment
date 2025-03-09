# SwiftUI List with Custom Cells, Navigation, and Animations

This SwiftUI app demonstrates how to display a list of items with custom cells, where each cell contains an image and text. The app allows for navigation to a detail view when an item is selected and includes animations when items are added or removed from the list.

## Features

- **List View**: Displays a dynamic list of items.
- **Custom Cells**: Each list item includes both an image and a text label.
- **Navigation**: Uses `NavigationStack` and `NavigationLink` to navigate to a detail view of each item.
- **Add/Remove Items**: Users can add or remove items from the list, with smooth animations for insertion and deletion.
- **Item Interaction**: The app supports item selection with a tap gesture for interaction.

## App Overview

### 1. **List View**
   - A `List` displays an array of items.
   - Each item is shown in a custom cell with an image and a label.
   
### 2. **Custom Cells**
   - List cells are designed to show both an image and text for each item, which helps enhance the user interface.

### 3. **NavigationStack and NavigationLink**
   - The app wraps the `List` in a `NavigationStack`, enabling navigation functionality.
   - When an item is tapped, a `NavigationLink` pushes a detail view to the screen, where more information about the selected item is displayed.

### 4. **Adding and Removing Items**
   - Items can be added using a button, and they appear with an animation.
   - Items can also be removed from the list using a swipe gesture, with smooth animations for deletion.

### 5. **Animations**
   - `.animation()` is used to animate the changes to the list when items are added or removed, ensuring a smooth transition and a pleasant user experience.

### 6. **Interaction**
   - Items can be interacted with using `.onTapGesture()`, which triggers actions when a user taps on a list item.

## Contributions

If you would like to contribute to this project:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request detailing the changes you made.

