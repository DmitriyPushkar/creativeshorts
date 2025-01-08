# Application Description

## Current State of the Application
The current version of the application includes three microservices:
1. **VideoCreator** – responsible for video content creation.
2. **VoiceOver** – handles voiceover generation.
3. **Storage** – manages application data and temporarily performs part of the functionality planned for the `Scenario` microservice.

The application is built using **Java 21**. Deployment is managed via **docker-compose**, which is temporarily located in the `Storage` microservice directory.

## Planned Architecture
The application will consist of six microservices:
1. **VideoCreator** – handles video content creation.
2. **VoiceOver** – generates voiceover.
3. **Storage** – manages application data.
4. **Scenario** – generates scenarios based on user data and keywords.
5. **Music** – selects music to accompany videos.
6. **VideoRecommender** – provides video material recommendations to enhance content quality.

## Development Roadmap
In future versions, the following microservices will be added:
- **Scenario** – to handle scenario generation.
- **Music** – to automate the selection of music tracks.
- **VideoRecommender** – to recommend video materials for better content creation.
