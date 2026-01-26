# ❌ Tic-Tac-Toe (XO) Game - WinForms

A sleek and fully functional **Tic-Tac-Toe** game developed using C# and Windows Forms. This project showcases the ability to combine GUI elements with complex game logic to create an engaging user experience.

---

## 🌟 Key Features & Strengths

- **🎨 Custom Graphics (GDI+):** Unlike basic implementations, this project uses the `Paint` event and `e.Graphics.DrawLine` to programmatically draw a clean, professional game grid.
- **🧠 Smart Win Detection:** Implements a robust checking algorithm that monitors all possible winning combinations (Rows, Columns, and Diagonals) after every move.
- **🔄 State Management:** Uses `Enums` and `Structs` to track player turns (Player 1 vs Player 2), game status (In Progress, Winner, or Draw), and move counts.
- **✨ Visual Feedback:** - Highlights the winning buttons in **GreenYellow** when a player wins.
  - Updates icons (X and O) dynamically from embedded resources.
  - Real-time status bar showing whose turn it is and the final result.
- **♻️ Seamless Restart:** A dedicated reset function that clears the board, resets the logic, and triggers a UI redraw without restarting the application.

---

## 🧠 Technical Highlights

This project was built during **C# WinForms Basics Course**. It highlights:
- **Event Handling:** Efficient use of button click events to manage the game flow.
- **GDI+ Basics:** Drawing custom shapes and lines directly onto the Form.
- **Logical Enums:** Using `enum` to represent `enPlayer` and `enWinner` for more readable and maintainable code.
- **UI Responsiveness:** Using `MessageBox` to announce game results and handle user confirmation for restarting.

---

## 📂 Project Preview

- **Players:** Two-player local mode (X and O).
- **Grid:** 3x3 interactive board.
- **Status:** Integrated labels for "Turn" and "Winner" tracking.

---

## 🚀 How to Run

1. **Prerequisites:** Ensure you have Visual Studio installed with the **.NET Desktop Development** workload.
2. **Clone the repo:**
   ```bash
   git clone [https://github.com/YourUsername/Tic-Tac-Toe-WinForms.git](https://github.com/YourUsername/Tic-Tac-Toe-WinForms.git)
   ```
3. Open the solution: Open the XO-Game-Final.sln file.
4. Build & Run: Press F5 to start the game.

---
## 👨‍💻 Author
Mohamed Ragheb Passionate about turning logic into interactive experiences.

---

If you enjoyed playing this or found the code useful, give it a ⭐!
