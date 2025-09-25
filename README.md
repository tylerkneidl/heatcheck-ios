# HeatCheck iOS

An iOS application for HeatCheck.

## Overview

HeatCheck iOS is a native iOS application built with Swift and SwiftUI.

## Requirements

- iOS 15.0+
- Xcode 14.0+
- Swift 5.7+

## Getting Started

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd heatcheck-ios
   ```

2. Open the project in Xcode:
   ```bash
   open HeatCheck.xcodeproj
   ```
   or
   ```bash
   open HeatCheck.xcworkspace  # if using CocoaPods
   ```

3. Build and run the project in Xcode

## Project Structure

```
HeatCheck/
├── HeatCheck/              # Main app source code
│   ├── Views/              # SwiftUI views
│   ├── Models/             # Data models
│   ├── ViewModels/         # View models
│   ├── Services/           # API and data services
│   ├── Utils/              # Utility classes and extensions
│   └── Resources/          # Assets, strings, etc.
├── HeatCheckTests/         # Unit tests
└── HeatCheckUITests/       # UI tests
```

## Development

### Architecture

This project follows the MVVM (Model-View-ViewModel) architecture pattern with SwiftUI.

### Dependencies

- SwiftUI for UI
- Combine for reactive programming
- URLSession for networking

### Code Style

- Follow Swift API Design Guidelines
- Use SwiftLint for code formatting
- Write unit tests for business logic

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

## License

[Add your license information here]

## Contact

[Add contact information here]
