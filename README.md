# 🎮 Princess Coin Catcher Game 👑✨

Welcome to the **Princess Coin Catcher Game**! A fun and interactive experience where you control a princess to catch falling coins. This project combines creativity, hardware, and software to create an engaging game that includes custom graphics, sound effects, real-time gameplay, and a few surprises along the way! 🚀

---

## 🏁 **Starting the Game**
When you first power up the game, you'll be greeted by a **Welcome Page**. The screen will display the rules and instructions, guiding you to the **physical buttons** on the **STM32F031x6 microcontroller (Nucleo board)**:
- **Left Button**: Press the **Left Button** to **start the game**. Once pressed, the game begins, and the princess starts catching falling coins! 🌟  
- **45-Second Countdown**: A **45-second countdown** will begin after pressing the Left Button. You must catch as many coins as you can before the timer runs out, or before you lose all your lives! ⏳

---

## 🕹️ **How It Works**
- **Control the Princess**: Use your **laptop keyboard** to move the princess left or right to catch the falling coins.  
- **Game Logic**: The game runs on an **STM32F031x6 microcontroller (Nucleo board)**, which connects to your laptop via USB to capture player input in real-time.  

---

## 🌟 **Features**
### 🎨 **Custom Graphics**
All the in-game visuals—including the princess, coins, and background were designed by me and the team, adding a unique and personal touch to the game.

### 💡 **LED Lives System**
- The player starts with **3 lives**, represented by **LEDs** on the Nucleo board.  
- Each time a life is lost, one LED turns off.  
- When all lives are lost, the LEDs **flash 3 times** to signal the end of the game.

### ⏳ **Countdown Timer**
- A **45-second countdown** is displayed on the screen. The player must catch as many coins as possible before the time runs out.  
- If the timer reaches zero, or if the player loses all lives, the game is over.

### 🎵 **Immersive Sound Effects**
- A **theme song** plays continuously throughout the game, created with a buzzer on the microcontroller that plays musical notes.  
- When the player loses a life or the game ends, a **game-over sound** is triggered to conclude the experience.

### 📜 **Game Over Page**
Once the player loses all lives or the timer runs out, the **Game Over Page** appears, displaying the player's score at the top left of the screen.  
- Here, the player is instructed to **press the Right Button** on the Nucleo board to **restart the game** and try to beat their previous score! 🏆

---

## 🏅 **Scoring**
- Each time the princess catches a coin, the player's **score** increments by **1**.  
- The current score is displayed at the **top-left corner** of the screen.  
- Your final score is shown on the **Game Over Page** after the game ends.

---

## 🤝 **Teamwork and Learning**
This was a **group project** where we split tasks so that each team member could contribute to different aspects of the game. This approach allowed everyone to gain hands-on experience in all areas, including:  
- 🎨 **Graphics design**  
- 🧩 **Game logic and coding**  
- 🛠️ **Hardware integration**  

By sharing responsibilities, we learned how to work together, solve problems, and build a project from start to finish, fostering a comprehensive learning experience! 🌱

---

💡 **Takeaway**: This project blends hardware and software to create an engaging, interactive game, providing an opportunity for creative expression and technical skill-building! 🎉
