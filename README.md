# Ayat Tech Solution Starter Project with Admin Dashboard

A new Flutter project.

## Getting Started

Project Structure
Understanding the project structure is essential for navigating and customizing the app effectively.
Below is a simplified tree structure of the project, focusing on the key directories and files.
```
lib/
├── app/                  # Core application logic, data models, repositories, and pages.
│   ├── core/             # Core utilities: helpers, static configs, styles, themes, and types.
│   ├── data/             # Data layer: models and repositories for API communication.
│   ├── middlewares/      # Middleware logic (e.g., authentication checks).
│   ├── pages/            # Screens/pages of the app, organized by feature (auth, common, landlord, tenant).
│   ├── routes/           # Routing configuration for navigation.
│   ├── services/         # Shared services (API client, global listeners, localization, etc.).
│   └── widgets/          # Reusable custom widgets used across the app.

assets/                   # Static assets like images, icons, JSON files, and shapes.
│   ├── app/              # App-specific assets (icons, splash screen, background images).
│   ├── icons/            # Icons used throughout the app (e.g., payment, room features).
│   ├── images/           # Images, including onboarding screen visuals.
│   ├── json/             # JSON files for static data (e.g., country lists).
│   └── shapes/           # Shape assets (placeholders, loading spinners, error messages).

i18n/                     # Localization files for translations (e.g., en.i18n.json, fr.i18n.json).

dev_tool/                 # Development tools and scripts (e.g., customization scripts).

main.dart                 # Entry point of the Flutter application.
pubspec.yaml              # Configuration file for dependencies and assets.
customization.yaml        # Contains easy customization configuration (Detailed in step 5).
```
