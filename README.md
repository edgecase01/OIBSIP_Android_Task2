# ⚖️ Unit Converter

A straightforward, reliable Android application for converting weights between **Kilograms (KG)** and **Pounds (LB)**. This version features a classic user interface using a selection dropdown and an explicit action button, ideal for users who prefer a traditional workflow.

https://github.com/user-attachments/assets/ac0e3165-4401-4c0a-9d7f-91bca0f2a16c

## ✨ Features

- **Dropdown Selection:** Uses a standard `Spinner` to toggle between "Kilograms to Pounds" and "Pounds to Kilograms".
- **Explicit Calculation:** User-triggered conversion via a "Convert" button to prevent accidental data shifts.
- **Input Validation:** Built-in error handling to notify users if they attempt a conversion with an empty input field.
- **Android 15 Optimized:** Full support for **Edge-to-Edge** rendering and `WindowInsets` to ensure UI elements do not overlap with system bars.
- **Simple & Accessible:** Built with a clean `ConstraintLayout` for a responsive design across different screen sizes.

---

## 🛠️ Tech Stack

- **Language:** Java 17
- **UI Framework:** XML with Android Material Components
- **SDK Support:**
    - `compileSdk`: 35 (Android 15)
    - `targetSdk`: 35
    - `minSdk`: 24 (Android 7.0)
- **Architecture:** Standard Activity-based structure using `AppCompatActivity`.

---

## 🚀 Getting Started

### Prerequisites
- Android Studio **Ladybug** (2024.2.1) or later.
- Java Development Kit (JDK) 17.

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/edgecase01/OIBSIP_Android_Task2.git
   ```
2. **Import Project:**
   - Open Android Studio, select **Open**, and navigate to the project folder.
3. **Gradle Sync:**
   - Allow Android Studio to sync the Gradle files and download required SDK 35 platforms.
4. **Deploy:**
   - Connect your device or start an emulator and click the **Run** icon.

---

## 📂 Project Structure

- **`MainActivity.java`**: Implements the conversion math, spinner selection logic, and Android 15 edge-to-edge UI adjustments.
- **`activity_main.xml`**: Layout containing the title, numeric input, dropdown (spinner), and action button.
- **`strings.xml`**: Centralized storage for app text and the conversion option array.

---

## 📝 Usage

1. Enter a numerical value into the input field.
2. Choose your conversion direction (KG to LB or vice-versa) from the dropdown.
3. Press **Convert**.
4. View the result formatted to two decimal places below the button.
