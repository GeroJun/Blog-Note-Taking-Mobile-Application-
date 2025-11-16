# 📝 Blog Note-Taking Mobile Application

A feature-rich mobile note-taking application built with React Native, designed to provide a seamless blogging and journaling experience on iOS and Android devices. This project demonstrates modern mobile development practices with real-time data persistence.

## 📱 Overview

This mobile application was developed as part of the CS440 (Mobile App Development) course at Azusa Pacific University. It features an intuitive interface for creating, editing, and managing notes with cloud synchronization capabilities through a localhost backend server.

**Project Timeline:** Fall 2023 (Sophomore Year)

## ✨ Features

- 📝 Create and edit notes with a clean, intuitive interface
- 💾 Real-time data persistence using ngrok-powered backend
- 🔄 Seamless navigation between screens using React Navigation
- 📱 Cross-platform support (iOS & Android)
- 🎨 Modern, responsive UI design
- ⚡ Fast and lightweight performance

## 🎥 Demo

https://github.com/GeroJun/Blog-Note-Taking-Mobile-Application-/assets/107790828/c9e6ce38-a11f-44d2-954b-e086fd686d95

## 🚀 Getting Started

### Prerequisites

- Node.js and npm installed on your machine
- Expo Go app installed on your mobile device ([iOS](https://apps.apple.com/app/expo-go/id982107779) | [Android](https://play.google.com/store/apps/details?id=host.exp.exponent))
- ngrok account for localhost tunneling

### Installation

1. Clone the repository
```bash
git clone https://github.com/GeroJun/Blog-Note-Taking-Mobile-Application-.git
cd Blog-Note-Taking-Mobile-Application-
```

2. Install dependencies
```bash
npm install
```

3. Set up ngrok tunnel
   - Start your local backend server
   - Create an ngrok tunnel to expose your localhost
   - Update the API endpoint in the application with your ngrok URL

4. Start the development server
```bash
npm start
```

5. Scan the QR code with your Expo Go app to run the application on your device

## 🛠️ Built With

- **[React Native](https://reactnative.dev/)** - Cross-platform mobile framework for building native apps using React
- **[Expo](https://expo.dev/)** - Development platform for rapid React Native app development
- **[React Navigation](https://reactnavigation.org/)** - Routing and navigation library for seamless screen transitions
- **[ngrok](https://ngrok.com/)** - Secure tunneling service for connecting the mobile app to a local backend server
- **JavaScript (ES6+)** - Primary programming language

## 📂 Project Structure

```
├── App.js                 # Main application component
├── app.json              # Expo configuration
├── babel.config.js       # Babel configuration
├── package.json          # Project dependencies
└── .gitignore           # Git ignore rules
```

## 🎓 Learning Outcomes

This project helped develop skills in:
- Mobile application development with React Native
- State management in mobile environments
- Navigation patterns in mobile apps
- Integration with backend services
- Cross-platform mobile UI/UX design
- Real-time data synchronization

## 📸 Screenshots

_Add screenshots of your app here to showcase the UI_

## 🔮 Future Enhancements

Potential improvements for future versions:
- [ ] User authentication and authorization
- [ ] Cloud storage integration (Firebase/AWS)
- [ ] Rich text editing capabilities
- [ ] Note categorization and tagging
- [ ] Search and filter functionality
- [ ] Dark mode support
- [ ] Offline mode with local storage
- [ ] Note sharing capabilities

## 📝 License

This project is open source and available for educational purposes.

## 👤 Author

**Victor Jun (GeroJun)**
- GitHub: [@GeroJun](https://github.com/GeroJun)

## 🙏 Acknowledgments

- Azusa Pacific University - CS440 Mobile App Development Course
- Course instructors and peers for guidance and feedback

---

⭐ If you found this project helpful, please consider giving it a star!
