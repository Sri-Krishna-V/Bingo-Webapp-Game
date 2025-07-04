A modern, responsive Bingo web application built with React, TypeScript, and Vite. Features a beautiful gradient design, smooth animations, and full game functionality.

## ✨ Features

- **🎲 Random Card Generation**: Each game generates a unique 5×5 Bingo card with random numbers
- **📞 Number Caller**: Automatically calls random numbers (B1-O75) following traditional Bingo rules
- **✅ Interactive Marking**: Click to mark called numbers on your card
- **🏆 Win Detection**: Automatically detects winning patterns (rows, columns, diagonals)
- **🎉 Victory Celebration**: Animated win screen with celebration effects
- **📱 Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **🎨 Modern UI**: Beautiful gradients, smooth animations, and intuitive interface

## 🎮 How to Play

1. **Start Game**: Click "Start Game" to begin calling numbers
2. **Mark Numbers**: When a number is called, click it on your card to mark it
3. **Win Condition**: Get 5 marked squares in a row (horizontal, vertical, or diagonal)
4. **Free Space**: The center square is automatically marked as "FREE"
5. **New Game**: Click "New Game" anytime to start fresh with a new card

## 🛠️ Tech Stack

- **React 18** - UI library for building interactive components
- **TypeScript** - Type safety and better developer experience
- **Vite** - Fast build tool and development server
- **CSS3** - Modern styling with gradients, animations, and responsive design

## 🚀 Getting Started

1. **Install dependencies**:

   ```bash
   npm install
   ```

2. **Start development server**:

   ```bash
   npm run dev
   ```

3. **Open your browser** and navigate to `http://localhost:5173`

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint for code quality checks

## 🎯 Game Rules

### Traditional Bingo Rules Implemented

- **B Column**: Numbers 1-15
- **I Column**: Numbers 16-30
- **N Column**: Numbers 31-45 (with FREE center space)
- **G Column**: Numbers 46-60
- **O Column**: Numbers 61-75

### Winning Patterns

- **Horizontal**: Any complete row
- **Vertical**: Any complete column
- **Diagonal**: Either diagonal line

---

**Enjoy playing Bingo!** 🎉
