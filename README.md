# Carros - Android Development Step-by-Step Tutorial

![Carros App Demo](carros.gif)

A comprehensive, step-by-step Android application tutorial that teaches modern Android development concepts through building a complete car catalog application. This project demonstrates best practices and essential Android components from basic setup to advanced features.

## Overview

This repository contains 23 progressive steps (Passos) that guide you through building a fully-featured Android application. Each step builds upon the previous one, introducing new concepts and features in a logical, easy-to-follow manner.

## Features

- **Material Design UI** - Modern, beautiful interface following Material Design guidelines
- **Navigation Drawer** - Side navigation menu with smooth animations
- **RecyclerView** - Efficient list display with custom adapters
- **Web Integration** - WebView for displaying web content
- **REST API** - Integration with web services (JSON/XML parsing)
- **SQLite Database** - Local data persistence
- **SharedPreferences** - User settings and preferences
- **Content Provider** - Data sharing between apps
- **Google Maps** - Location and map integration
- **Video Playback** - Multimedia support
- **Share Functionality** - Social sharing capabilities

## Project Structure

Each `Passo` (Step) directory contains a complete, buildable Android project demonstrating specific features:

### Step-by-Step Breakdown

| Step | Topic | Description |
|------|-------|-------------|
| **Passo01** | Project Setup | Initial Android project creation and configuration |
| **Passo02** | Toolbar | Adding and customizing the Action Bar/Toolbar |
| **Passo03-parte1** | Navigation Drawer | Basic navigation drawer implementation |
| **Passo03-parte2** | Material Design Nav | Enhanced nav drawer with Material Design |
| **Passo04** | Fragments | Navigation drawer integration with Fragments |
| **Passo05** | WebView | Displaying web content within the app |
| **Passo06** | RecyclerView | Implementing efficient lists with RecyclerView |
| **Passo07** | Detail Views | Car detail screens and navigation |
| **Passo08** | XML Parsing | Reading and parsing XML data |
| **Passo09** | JSON Parsing | Handling JSON data structures |
| **Passo10** | Web Services | RESTful API integration |
| **Passo11** | File Downloads | Downloading and caching files from web |
| **Passo12** | SharedPreferences | Storing user preferences locally |
| **Passo13** | Settings | Full settings screen implementation |
| **Passo14** | SQLite | Local database with SQLite |
| **Passo15** | Backup | Data backup and restore functionality |
| **Passo16** | Long Click | Handling long-press gestures |
| **Passo17** | Share | Social sharing integration |
| **Passo18** | Intents | Inter-app communication with Intents |
| **Passo19** | Video | Video playback functionality |
| **Passo20** | Maps | Google Maps integration |
| **Passo21** | Content Provider | Sharing data via Content Providers |
| **Passo22** | Gradle | Advanced Gradle build configuration |
| **Passo23** | Material Plus | Additional Material Design enhancements |

## Visual Demos

![Navigation Drawer Demo](NavDrawer-4-OK.gif)
![FAB Animation](FAB.gif)
![Scroll Effects](Scroll.gif)
![State List Animator](StateListAnimator.gif)

## Getting Started

### Prerequisites

- Android Studio (latest version recommended)
- JDK 8 or higher
- Android SDK with minimum API level support
- Basic knowledge of Java and Android development

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/carros.git
   cd carros
   ```

2. Choose the step you want to explore:
   ```bash
   cd Passo01-CriarProjeto/Carros
   ```

3. Open the project in Android Studio:
   - File → Open → Navigate to the selected Passo directory
   - Select the `Carros` folder
   - Wait for Gradle sync to complete

4. Run the project:
   - Connect an Android device or start an emulator
   - Click the "Run" button or press Shift+F10

### Learning Path

For beginners, it's recommended to follow the steps sequentially:

1. Start with **Passo01** to understand project structure
2. Progress through each step, comparing code changes
3. Run each version to see features in action
4. Experiment by modifying the code
5. Use the final version (**Passo23**) as a reference implementation

## Architecture

The project follows standard Android architecture patterns:

```
br.com.livroandroid.carros/
├── activity/          # Activities (screens)
├── adapter/           # RecyclerView and list adapters
├── domain/            # Business logic and models
├── fragments/         # Fragment components
└── CarrosApplication  # Application class
```

## Key Components

### Activities
- `MainActivity` - Main screen with navigation drawer
- `CarroActivity` - Car detail view
- `BaseActivity` - Shared activity functionality

### Adapters
- `CarroAdapter` - RecyclerView adapter for car lists
- `NavDrawerMenuAdapter` - Navigation drawer menu
- `TabsAdapter` - Tab layout for categorized views

### Domain Layer
- `Carro` - Car model/entity
- `CarroService` - Business logic for car operations

### Fragments
- `CarrosFragment` - Main car list display
- `CarrosTabFragment` - Tabbed interface for car categories
- `SiteLivroFragment` - WebView for website content

## Technologies Used

- **Android SDK** - Core Android framework
- **Support Library / AndroidX** - Backward compatibility
- **Material Design Components** - UI components
- **RecyclerView** - Efficient list rendering
- **Retrofit / HTTP** - Network requests
- **Gson** - JSON serialization
- **SQLite** - Local database
- **Google Play Services** - Maps and location
- **Gradle** - Build automation

## Build Variants

The project includes multiple build variants (demonstrated in Passo22):
- Debug/Release configurations
- Product flavors (e.g., "Azul", "Vermelho")
- Custom build configurations with different API keys

## License

This project is part of an educational book about Android development. Please refer to the book's license terms.

## Resources

- **Package**: `br.com.livroandroid.carros`
- **Min SDK**: Check individual Passo build.gradle files
- **Target SDK**: Check individual Passo build.gradle files

## Contributing

This is an educational project. If you find issues or have suggestions for improvements:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request with a clear description

## Acknowledgments

This project is based on educational material for teaching Android development concepts. Each step is carefully designed to introduce concepts progressively, making it easier for learners to understand complex Android features.

## Support

If you encounter issues or have questions:
- Check the specific Passo's README or documentation files
- Review the code comments for implementation details
- Compare with previous steps to understand changes

---

**Happy Coding!** Start with Passo01 and work your way through to become proficient in Android development.
