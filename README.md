# Smart AI Voice Assistant

A voice assistant built using Natural Language Processing (NLP), Machine Learning (ML), and Deep Learning (DL) techniques. The assistant can perform tasks like managing your schedule, controlling system applications, browsing the internet, and providing system status updates—all through voice commands.

### Project Layout

### Phases of Development

- **Phase 1**: **Text-to-Speech and Speech Recognition**

  - Implemented the basic text-to-speech (TTS) functionality using `pyttsx3` and speech-to-text using `speech_recognition`. The system was able to respond to simple voice commands.

- **Phase 2**: **App Control Integration**

  - Added the ability to open and close system applications like Notepad, Calculator, and Paint. The assistant can now handle basic system commands.

- **Phase 3**: **Intent Recognition with Machine Learning**

  - Integrated a machine learning-based intent recognition system. A chatbot was added to handle predefined intents such as greetings, social media access, and system status updates.

- **Phase 4**: **System Status Reporting**

  - Added functionality to report system information like CPU usage and battery percentage, giving the assistant a more interactive and informative role.

- **Phase 5**: **Final Integration and Testing**
  - Integrated all components, fine-tuned the model for faster response times, and conducted thorough testing to ensure seamless functionality.

### Tools and Technologies Used

- **Python 3.x**: The primary programming language for building the assistant.
- **pyttsx3**: For offline text-to-speech (TTS) conversion.
- **speech_recognition**: For converting speech to text.
- **os**: For controlling system applications (e.g., opening/closing apps).
- **psutil**: For retrieving system information such as CPU usage and battery status.
- **scikit-learn**: For building the machine learning model to classify user intents.
- **TensorFlow/Keras**: Used to build and train the deep learning model for intent classification.
