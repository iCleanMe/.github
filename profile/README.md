
# iCleanMe Organization

### Tidy spaces, happy faces! Fun meets clean! Emojis bring cheer to chores, uniting smiles and sparkling spaces.

Welcome to the iCleanMe GitHub organization, home to the modular components that power the iCleanMe app, designed to make it easy for people to maintain the state of their homes and belongings. As a solo developer, I've structured this organization to highlight the modularity, maintainability, and quality that define my approach to iOS development.

## Organization Overview

iCleanMe is not just an app; it’s a philosophy for keeping your spaces organized and your mind at ease. By breaking down the main features of the iCleanMe app into independent Swift packages, I'm hoping to showcase my commitment to clean architecture, easy-to-read code, and comprehensive testing.

## Public Repositories

### 1. [iCleanMeRooms](https://github.com/iCleanMe/iCleanMeRooms)
The `iCleanMeRooms` package handles the management of rooms within the iCleanMe app. Users can add, edit, reorder, and delete rooms, including personal rooms. While rooms can contain cleaning tasks, this module focuses solely on room management, with task deletion occurring automatically when a room is deleted. The `iCleanMeRooms` module is built with a comprehensive test suite, utilizing `NnTestKit` to ensure reliability and correctness.

### 2. [iCleanMeSharedUI](https://github.com/iCleanMe/iCleanMeSharedUI)
The `iCleanMeSharedUI` package encapsulates the shared UI components used across the iCleanMe app. This module is a dependency for other parts of the app, ensuring a consistent look and feel throughout the user interface. It relies on `NnSwiftUIKit`, another Swift package I developed, to streamline UI development. Unlike other modules, `iCleanMeSharedUI` does not contain tests, as it is solely focused on providing reusable UI elements.

## Development Philosophy

At the core of iCleanMe’s development is a strong emphasis on:

- **Modularity:** Each feature is isolated in its own Swift package, allowing for easy updates, testing, and reusability across projects.
- **Readability:** Writing clean and easy-to-read code is paramount. This ensures that the codebase is approachable and maintainable over time.
- **Maintainability:** The modular architecture supports long-term maintenance, enabling isolated changes without risking the integrity of other components.
- **Testing:** Thorough testing is critical to delivering a reliable user experience. The `iCleanMeRooms` module, for instance, is equipped with a comprehensive test suite using `NnTestKit`, ensuring each component functions as expected.
- **Architecture:** Leveraging Swift package modularity ensures that features are decoupled and can evolve independently. This structure allows for granular updates, facilitating more straightforward maintenance and reducing the risk of regressions.

## Contribution Guidelines

While I am not actively seeking collaborators, I welcome feature requests, issues, and discussions. The public repositories are open for exploration, and contributions that align with the project's philosophy are encouraged.
