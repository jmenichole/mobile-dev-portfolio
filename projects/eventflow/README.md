# EventFlow: Event Planning Toolkit

## Project Overview
EventFlow is a comprehensive toolkit for event planners to streamline workflows, manage vendor relationships, and track event metrics in real-time.

## Key Features
- Drag-and-drop schedule builder
- Vendor contract management
- Budget tracking and forecasting
- Attendee analytics dashboard
- Multi-user collaboration tools
- Document storage and sharing

## Technologies Used
- **Frontend:** Kotlin, Jetpack Compose
- **Database:** Room, SQLite
- **Charts:** MPAndroidChart
- **Authentication:** Firebase Authentication
- **Cloud Storage:** Cloud Firestore
- **Background Processing:** Work Manager

## Architecture
The application follows a clean architecture approach with the following components:
- **UI Layer:** Activities, Fragments, and Compose UI
- **Domain Layer:** Use cases and business logic
- **Data Layer:** Repositories and data sources

## Screenshots
[Include screenshots here]

## Development Process
1. **Discovery Phase:** Market research and feature planning
2. **Design Phase:** UI/UX design and information architecture
3. **Development Phase:** Incremental development with CI/CD
4. **QA Phase:** Automated and manual testing
5. **Release Phase:** Beta testing and production release

## Challenges and Solutions
- **Challenge:** Complex data relationships between events, vendors, and schedules
  - **Solution:** Implemented a robust relational database schema with Room

- **Challenge:** Real-time collaboration between multiple planners
  - **Solution:** Utilized Firestore real-time updates with conflict resolution

## Future Enhancements
- AI-powered budget optimization
- Vendor marketplace integration
- Advanced reporting features
- Template sharing between users

## Links
- [GitHub Repository](https://github.com/jmenichole/eventflow)
- [Google Play Download](#)