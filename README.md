# Offline Real-Time Speech Recognition in Java

**This application transcribes your speech to text in real time, entirely offline!**

## Features
- Fully offline (uses Vosk library and local models)
- Modern JavaFX GUI: Start/Stop buttons, live speech transcripts
- Cross-platform (Windows, Mac, Linux), Maven-based

## Setup

### Prerequisites
- Java 11+ (recommend Java 17)
- Maven
- [JavaFX SDK 17+](https://openjfx.io/)
- [Vosk model](https://alphacephei.com/vosk/models), e.g., `vosk-model-small-en-us-0.15`

### Installation
1. Clone this repository.
2. Place a Vosk model in `src/main/resources/model/`
3. Build: `mvn clean package`
4. Run using JavaFX VM arguments
