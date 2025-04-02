# 🎓 Degree Management App

A Flutter application for managing academic degrees, allowing users to add, view, edit, and delete degree records with a clean and intuitive UI.

## 📌 Features
✅ View a list of all saved degrees
✅ Detailed view for each degree
✅ Add new degrees with a form
✅ Edit existing degrees
✅ Delete degrees with confirmation
✅ Input validation for all fields
✅ SQLite database integration for persistence

## 🏗 App Structure

### `main.dart`
- **DegreeManagementApp**: The main app widget
- **DegreeListScreen**: Displays all saved degrees with options to add, view, edit, and delete
- **DegreeDetailScreen**: Shows detailed information about a selected degree
- **DegreeFormScreen**: Form for adding and editing degrees

### `degree.dart`
Defines the **Degree** class with properties:
-  `id` – Unique identifier
-  `name` – Name of the degree
-  `field` – Field of study
-  `institution` – School/university name
-  `gpa` – Grade point average
-  `dateEarned` – Date the degree was earned

Includes methods for converting to/from database map format.

### `database_helper.dart`
Manages SQLite database operations with full CRUD functionality:
-  **Create**: `insertDegree()`
-  **Read**: `getDegrees()`, `getDegree()`
-  **Update**: `updateDegree()`
-  **Delete**: `deleteDegree()`

##  Dependencies (`pubspec.yaml`)
- `sqflite` – For SQLite database functionality 🗄
- `path` – For file path management 📂

##  How to Run the Application
1. Create a new Flutter project:
   ```sh
   flutter create degree_management_app
   ```
2. Replace the default files with these files.
3. Install dependencies:
   ```sh
   flutter pub get
   ```
4. Run the app on an emulator or physical device:
   ```sh
   flutter run
   ```

##  UI Highlights
 Clean and intuitive design
 List view of all degrees
 Detailed degree view
 Easy-to-use input forms
 Delete confirmation dialog
 Input validation

---

## 📬 Contact
🔗 **Follow Me:** [CodeShow LapZ](https://codeshow-lapz.web.app/presentation) 
