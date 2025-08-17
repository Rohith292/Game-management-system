# 🎮 Game Management System (Java Desktop Suite)

The **Game Management System** is a Java desktop app offering multiple classic games with login/registration and a central selection menu. It includes score tracking and a GUI built using Java Swing.

---

## 🕹️ Game Modules

### 📝 Register
Sign-up form for new users.

![Register](./images/Register.png)

---

### 🔐 Login
Simple login form for existing users.

![Login](./images/Login.png)

---

### 🎮 Game Selection Hub
Launch any game or view scores from a single interface.

![Game Selection](./images/GameSelection.png)

---

### ⌨️ Game Running (Username Prompt)
Prompts for username before launching a game session.

![Game Running](./images/GameRunning.png)

---

### 🐤 Flappy Bird
Side-scrolling game where you control a bird flying between pipes.

![Flappy Bird](./images/FlappyBird.png)

---

### 👻 Pacman
Collect dots while avoiding ghosts.

![Pacman](./images/pacman.png)

---

### 👾 Space Invader
Shoot aliens before they reach you.

![Space Invader](./images/SpaceInvader.png)

---

### 💣 Minesweeper
Click tiles and avoid hidden mines.

![Minesweeper](./images/minesweeper.png)

---

### 📊 View Scores
Displays past game scores by user.

![View Scores](./images/ViewScores.png)

---

## 🛠️ Technologies Used

- **Language**: Java  
- **UI**: Java Swing  
- **Architecture**: OOP  
- **Data Handling**: File-based (or in-memory)

---

## 🚀 How to Run

```bash
javac -d bin src/**/*.java
java -cp bin ui.GameSelection
