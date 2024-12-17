# 🍳 Mood-Based Recipe App

### A SwiftUI-based iOS Application that recommends energy-boosting recipes tailored to your mood! 🌟

---

## 💼 **About the Project**

The Mood-Based Recipe App is a user-friendly iOS application designed to enhance your mood and energy levels through delicious, healthy recipes. Each mood is paired with five recipes specifically curated to improve your emotional state.

Whether you're feeling **Happy**, **Sad**, **Relaxed**, **Angry**, **Tired**, or in a **Romantic** mood, this app has something for everyone! 

---

## 🎯 **Features**

💯 **Mood Selection**:  
Choose from six moods (Happy 😊, Sad 🥺, Relaxed 😌, Angry 😠, Tired 😫, Romantic 🥰).  

💯 **Curated Recipes**:  
Each mood has 5 energy-boosting recipes tailored to support or improve how you feel.  

💯 **Beautiful UI**:  
A clean and modern interface built with **SwiftUI** for a seamless experience.  

💯 **Navigation**:  
Effortlessly navigate between moods and detailed recipe pages.  

---

## 📱 **Screenshots**

| **Home Screen** | **Mood Selection** | **Recipe Detail View** |
|-----------------|--------------------|------------------------|
| ![Home](./screenshots/home.png) | ![Mood](./screenshots/mood.png) | ![Detail](./screenshots/detail.png) |

---

## 🛠 **Tech Stack**

- **SwiftUI**: Modern UI framework for iOS.  
- **Xcode**: IDE for iOS development.  
- **iOS 15+**: Target iOS version for the app.  

---

## 🚀 **Getting Started**

### **Prerequisites**
- macOS with Xcode installed (version 13+ recommended).  
- Basic understanding of Swift and SwiftUI.

---

### **Installation**

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/mood-recipe-app.git
   cd mood-recipe-app
   ```

2. **Open in Xcode**:  
   Open the `.xcodeproj` file using Xcode.

3. **Build and Run**:  
   Run the project on a simulator or a real device using the "Play" button in Xcode.

---

## 📂 **Project Structure**

```
MoodRecipeApp/
│
├── Assets/                     # Images, colors, and assets
├── Views/
│   ├── ContentView.swift       # Main mood selection screen
│   ├── HappyDetailView.swift   # Recipes for 'Happy' mood
│   ├── SadDetailView.swift     # Recipes for 'Sad' mood
│   ├── RelaxDetailView.swift   # Recipes for 'Relaxed' mood
│   ├── AngryDetailView.swift   # Recipes for 'Angry' mood
│   ├── TiredDetailView.swift   # Recipes for 'Tired' mood
│   └── RomanticDetailView.swift # Recipes for 'Romantic' mood
│
├── Models/                     # Recipe data models
├── MainproApp.swift            # App entry point
└── README.md                   # Project documentation
```

---

## 💡 **How It Works**

1. The user selects a mood from the main screen.  
2. The app navigates to a detail view with 5 recipes tailored for the selected mood.  
3. Each recipe displays:  
   - **Recipe name**  
   - **Mood-boosting ingredients**  
   - **Benefits for your mood**  

---

## 📖 **Future Improvements**

- Add detailed step-by-step recipe instructions.  
- Integrate animations for mood transitions.  
- Include a search feature to find recipes by ingredients.  
- Implement a favorites list to save recipes.  
- Add backend support for dynamic recipe updates.

---

## 👌 **Contributions**

Contributions are welcome! 🎉  
1. Fork this repository.  
2. Create a feature branch:  
   ```bash
   git checkout -b feature/your-feature-name
   ```  
3. Commit your changes:  
   ```bash
   git commit -m "Add your feature"  
   ```  
4. Push to your branch and submit a Pull Request.

---

## 📜 **License**

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## 👩‍💻 **Author**

**Fatima**  
- Project Creator  
- Passionate iOS Developer 📱  

---

## 🌟 **Acknowledgments**

Special thanks to resources and research papers that inspired mood-based recipe creation.  
Icons by [Emoji Icons](https://emojipedia.org/).

---
