# 📚 Quiz App

An interactive, responsive quiz application that fetches questions from the [Open Trivia Database (OpenTDB)](https://opentdb.com/), lets users select question count, category, difficulty, and time per question. It features real-time countdown, progress tracking, answer validation, and a final score screen.

## 🚀 Features
- Customizable quiz settings (question count, category, difficulty, timer)
- Live countdown timer with progress bar
- Visual feedback for correct and wrong answers
- Final score screen
- Restart functionality
- Audio alert during last 3 seconds of countdown

## 📁 Project Structure
```
├── index.html        # Main HTML file
├── style.css         # Styling for the app
├── script.js         # Core logic and interactivity
├── countdown.mp3     # Audio played during countdown
```

## 🔧 How to Use

1. **Open `index.html` in any browser.**
2. **Choose quiz settings.**
3. **Click "Start Quiz".**
4. **Select answers and click "Submit".**
5. **Click "Next" to proceed.**
6. **View your score at the end and optionally restart.**

## 📦 Dependencies
- Font Awesome (CDN)
- Google Fonts (Poppins)
- OpenTDB API

## 📌 Notes
- Make sure `countdown.mp3` is in the same folder as `index.html` for the countdown audio to work.
- If hosted online, ensure audio files have proper permissions for playback.

## 💡 Future Enhancements (Optional Ideas)
- Add timer pause/resume functionality
- Add animations for transitions between questions
- Store scores in local storage or a database
- Mobile responsiveness improvements
