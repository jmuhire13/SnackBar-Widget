# SnackBar Flutter Demo

A Flutter application demonstrating SnackBar widgets with custom styling and interactive actions.

## What is a SnackBar?

A SnackBar is a brief message that appears at the bottom of the screen to provide feedback about an action. It can contain text and optional action buttons, and typically disappears automatically after a few seconds.

## What it does

Shows a "No Internet Connection" SnackBar with an undo button when you tap "Connect Wifi". The SnackBar appears at the bottom with a purple background and automatically dismisses after 2 seconds.

## Getting Started

### Prerequisites
- Flutter SDK installed
- Device or emulator

### Installation

1. Clone this repository
2. Install dependencies:
   ```bash
   flutter pub get
   ```
3. Run the app:
   ```bash
   flutter run
   ```

## How to Use

1. Open the app
2. Tap the "Connect Wifi" button
3. A SnackBar will appear showing "No Internet Connection" with an "Undo" button
4. The SnackBar will disappear automatically after 2 seconds

## Code Structure

- `lib/main.dart` - App entry point with Material theme
- `lib/pages/snack_bar.dart` - SnackBar implementation and UI
