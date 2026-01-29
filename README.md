# Cross-Platform To-Do List App

## Framework Used
**Flutter** - A cross-platform UI framework developed by Google that uses the Dart programming language.

## Native vs Cross-Platform Development

### Native Development
- **Codebase**: Separate per platform (Kotlin/Java for Android, Swift/Objective-C for iOS)
- **Performance**: Highest possible performance
- **Development Speed**: Slower due to maintaining multiple codebases
- **Maintenance**: Higher cost and complexity
- **Platform APIs**: Full access to all device features

### Cross-Platform Development
- **Codebase**: Single shared codebase for multiple platforms
- **Performance**: Near-native performance with minimal overhead
- **Development Speed**: Faster development with shared business logic
- **Maintenance**: Lower cost and complexity
- **Platform APIs**: Access via plugins and frameworks

### Why Flutter for This Project?
- **Consistent UI**: Same look and feel across Android and iOS
- **High Performance**: Compiled to native ARM code
- **Hot Reload**: Rapid development and testing
- **Rich UI Components**: Material Design components built-in
- **Single Codebase**: One codebase maintains both platforms

## App Features

### Minimum Functional Requirements ✅
1. **Text input for new tasks** - TextField widget with hint text
2. **Button to add tasks** - ElevatedButton that adds tasks to the list
3. **List displaying all tasks** - ListView.builder showing all tasks
4. **Ability to remove tasks** - Delete button for each task item
5. **Single screen UI** - All functionality on one screen

### Implementation Details
- **State Management**: StatefulWidget with setState()
- **UI Layout**: Column with Row for input and ListView for tasks
- **User Experience**: Enter key support for quick task addition
- **Visual Design**: Material Design with proper spacing and icons

## Project Structure
```
MobileDev-StudentName/
│
├── app/
│   └── todo_app/
│       ├── pubspec.yaml
│       └── lib/
│           └── main.dart
├── screenshots/
│   ├── add_task.png
│   ├── task_list.png
│   └── delete_task.png
└── README.md
```

## How to Run
1. Install Flutter SDK
2. Run `flutter pub get` in the todo_app directory
3. Connect a device or start an emulator
4. Run `flutter run`

## Key Takeaway
Cross-platform frameworks like Flutter enable faster development by sharing a single codebase across platforms while maintaining high performance and consistent user experience. This demonstrates the power of modern mobile development approaches compared to traditional native development.
