# ConBuddy: Convention Companion App

## Project Overview
ConBuddy is a mobile application designed to enhance the convention experience by helping attendees manage their schedules, connect with other attendees, and navigate large convention spaces efficiently.

## Key Features
- Personalized schedule builder
- Friend finder with proximity alerts
- Vendor booth locator
- Panel reminders and ratings
- Offline mode for poor connectivity areas
- Social sharing of favorite events

## Technologies Used
- **iOS:** Swift, SwiftUI, Core Data
- **Android:** Kotlin, Jetpack Compose, Room
- **Backend:** Firebase Cloud Functions
- **API:** GraphQL
- **Analytics:** Firebase Analytics

## Architecture
The application follows the MVVM (Model-View-ViewModel) architecture pattern:
- **Models:** Data structures and business logic
- **Views:** UI components and screens
- **ViewModels:** State management and business logic

## Screenshots
[Include screenshots here]

## Development Process
1. **Research Phase:** User interviews and needs assessment
2. **Design Phase:** UI/UX design and prototyping
3. **Implementation Phase:** Feature development and testing
4. **Beta Testing:** Limited release to early adopters
5. **Release Phase:** Full release with monitoring

## Challenges and Solutions
- **Challenge:** Indoor positioning without reliable GPS
  - **Solution:** Implemented Bluetooth beacon integration and QR code checkpoints

- **Challenge:** Managing schedule conflicts
  - **Solution:** Developed an intelligent conflict resolution system with alternatives

## Future Enhancements
- Integration with popular calendar apps
- Augmented reality navigation
- Voice assistant for hands-free operation
- Cross-convention profile portability

## Links
- [GitHub Repository](https://github.com/jmenichole/conbuddy)
- [App Store Download](#)
- [Google Play Download](#)