
# FSEI Management of Relations with Teachers

<img src="https://github.com/Yacine300/FSEI-Gestion-des-Relations-avec-Enseignants/blob/main/assets/id/id_1.png" alt="ScholaSphere">


This Flutter application is designed based on the requirements of FSEI Mostaganem, Algeria. It aims to facilitate the management of relations between teachers and administrative staff. The application provides multiple interfaces to cater to different roles within the faculty, including "Responsable Filière," "Chef Département," "Administrateur," and "Teacher."

## Features

The application offers the following features:

- **Multiple Interfaces**:
  - **Responsable Filière (RF)**: Manages their respective fields and oversees the related activities. They can also perform teacher activities.
  - **Chef Département (CD)**: Manages their department and supervises the related activities. They can also perform teacher activities.
  - **Administrateur**: Manages modules, teachers, and administrative tasks.
  - **Teacher**: Handles teaching activities and interacts with students and other staff members.

## Roles and Responsibilities

### Responsable Filière (RF)
- Manage the curriculum and modules for their specific field.
- Oversee the performance and activities of teachers within their field.
- Can also take on teaching responsibilities.

### Chef Département (CD)
- Supervise the department and ensure the smooth operation of departmental activities.
- Manage departmental resources and staff.
- Can also take on teaching responsibilities.

### Administrateur
- Manage the overall system, including adding or removing modules and teachers.
- Ensure that all administrative tasks are performed efficiently.
- Oversee the smooth functioning of the application.

### Teacher
- Handle teaching activities, including creating and managing course materials.
- Interact with students and provide academic support.
- Participate in departmental and faculty meetings.

## Getting Started

To get started with the application, follow these steps:

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/your-repository/fsei-management.git
   cd fsei-management
   ```

2. **Install Dependencies**:
   ```sh
   flutter pub get
   ```

3. **Run the Application**:
   ```sh
   flutter run
   ```

## Folder Structure

The application follows the MVVM (Model-View-ViewModel) pattern for a clean and maintainable codebase. Here's an overview of the folder structure:

```
lib/
|-- models/        # Contains data models
|-- viewmodels/    # Contains ViewModel classes for state management
|-- views/
|   |-- screens/   # Contains full-screen UI components (pages)
|   |-- widgets/   # Contains smaller, reusable UI components
|-- theming/       # Contains theming-related files
|-- enums/         # Contains enumeration classes
|-- main.dart      # Entry point of the application
```

## Contributing

We welcome contributions from the community. To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

<img src="https://github.com/Yacine300/FSEI-Gestion-des-Relations-avec-Enseignants/blob/main/assets/id/id_2.png" alt="ScholaSphere">
