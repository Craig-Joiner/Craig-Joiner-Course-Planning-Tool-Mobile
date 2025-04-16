📱 Course Planning Tool (C# .NET MAUI Mobile)

This is a C# mobile application built with .NET MAUI, designed to help students organize and manage academic terms, courses, and assessments. The app offers a clean interface with custom navigation (no AppShell), and stores data locally using SQLite. Built using the MVVM architecture for a maintainable and scalable structure.

---

🧩 Features

- View all terms, courses, and assessments
- Add new terms, courses, and assessments
- Edit or delete any item with validation
- Navigate using custom buttons (instead of AppShell)
- View term-specific course and assessment lists
- Offline data storage with SQLite
- Smooth MVVM pattern for clean code separation

---

🛠️ Technologies Used

- **Language:** C#
- **Framework:** .NET 9 (.NET MAUI)
- **IDE:** Visual Studio 2022+
- **UI:** XAML for mobile layout
- **Architecture:** MVVM (Model-View-ViewModel)
- **Database:** SQLite (via SQLite-net)

---

🗂️ Project Structure
/CoursePlanningTool 
├── Views/ │ 
├── HomePage.xaml # Displays list of terms │ 
├── AddTermPage.xaml # Form to add a new term │ 
├── EditTermPage.xaml # Form to edit a term │ 
├── AddCoursePage.xaml # Form to add a new course │ 
├── EditCoursePage.xaml # Form to edit a course │ 
├── AddAssessmentPage.xaml # Form to add a new assessment │ 
├── EditAssessmentPage.xaml # Form to edit an assessment

├── ViewModels/ │ 
├── HomeViewModel.cs │ 
├── AddTermViewModel.cs │ 
├── EditCourseViewModel.cs │
├── AddAssessmentViewModel.cs 
│ └── etc...

├── Models/ │ 
├── Term.cs │ 
├── Course.cs │ 
├── Assessment.cs

├── Database/ │ 
├── DatabaseService.cs # Handles SQLite DB operations

├── App.xaml.cs # App lifecycle & navigation logic 
├── MauiProgram.cs # Dependency injection setup 
└── MainPage.xaml # (If used for initial routing)

---

🙋‍♂️ Author
Craig Joiner
https://github.com/Craig-Joiner
"""
