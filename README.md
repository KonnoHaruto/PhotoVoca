# PhotoVoca

English | [日本語](README_JP.md)

<p align="center">
  <img src="assets/images/photovoca.png" alt="PhotoVoca Logo" width="200"/>
</p>

A Flutter application that transforms everyday objects into English vocabulary learning opportunities through camera-based object recognition.

**🏆 Excellence Award Winner at [RSS Hackathon 2025 Beyond "あたりまえ"の、その先へ](https://www.craftstadium.com/hackathon/rss-hackathon-2025-beyond) - September 7, 2025**


## App Screen

<table>
  <tbody>
    <tr>
      <td align="center">
        <img src="https://github.com/user-attachments/assets/79d7d9a0-0149-40bd-9387-d5bf152c5bdb" alt="OCR Screen" width="220">
      </td>
      <td align="center">
        <img src="https://github.com/user-attachments/assets/ca478625-d784-4f7f-851e-934c269cd8a2" alt="Preview Screen" width="220">
      </td>
    </tr>
    <tr>
      <td align="center"><sub>Identifies and highlights objects captured by the camera.</sub></td>
      <td align="center"><sub>Preview the tapped object to display the actual English word.</sub></td>
    </tr>
    <tr>
      <td align="center">
        <img src="https://github.com/user-attachments/assets/151b8ce3-6f3e-46ec-8b58-848891de8db3" alt="Quiz Screen" width="220">
      </td>
      <td align="center">
        <img src="https://github.com/user-attachments/assets/d79be5a1-bd2b-4d04-b6c5-4607ac2dc68c" alt="Quiz Screen" width="220">
      </td>
    </tr>
    <tr>
      <td align="center"><sub>You can study words added to your vocabulary list by turning them into quizzes.</sub></td>
      <td align="center"><sub>It features a card-flipping animation, making learning fun.</sub></td>
    </tr>
  </tbody>
</table>



## Overview

PhotoVoca is a mobile app that helps users learn English vocabulary by simply taking photos of objects around them. By combining Google ML Kit's object detection with Gemini AI's description generation, it creates an engaging and memorable learning experience that connects visual recognition with language acquisition.

## Key Features

### Camera & Object Recognition
- Real-time object detection powered by Google ML Kit
- Automatic cropping of detected objects
- Multiple object selection from a single photo

### AI-Powered Content Generation
- Gemini AI generates English names and descriptions
- Context-aware practical example sentences
- Visual-linguistic association for better retention

### Flashcard Learning System
- Captured objects saved as flashcards
- Tap to reveal answers
- Swipe navigation between cards
- Learning history tracking

### Data Management
- Local SQLite database storage
- Persistent learning history
- Offline learning capability


## Tech Stack

- **Framework**: Flutter
- **State Management**: Riverpod
- **Routing**: go_router
- **AI/ML**:
  - Google Generative AI (Gemini)
  - Google ML Kit Object Detection
- **Camera**: camera
- **Database**: Drift (SQLite)
- **Image Processing**: image


## Roadmap

- Voice pronunciation feature
- Learning progress visualization
- Category-based vocabulary organization
- Multi-language support
- Cloud synchronization

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Contact

For questions or suggestions, please open an issue on GitHub.
