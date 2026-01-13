# Stone Paper Scissors Game ✂️📄🗿

A **fully functional Rock Paper Scissors game** with live scoring, dynamic win/loss messages, and smooth visual feedback. Built with vanilla HTML, CSS, and JavaScript.

## ✨ Features
- **Complete RPS Logic** - Rock beats Scissors, Paper beats Rock, Scissors beats Paper
- **Live Score Tracking** - `userScore` vs `compScore` displayed in real-time
- **Dynamic Messages** - Win (green), Loss (red), Draw (navy) with descriptive text
- **Random Computer AI** - `genCompChoice()` picks from ["rock", "paper", "scissors"]
- **Hover Effects** - Circular buttons fade + black overlay
- **Professional Dark Theme** - Navy blue (#081b31) headers & messages

## 🎮 Complete Game Flow
CLICK → Rock/Paper/Scissors (gets ID attribute)
AI → Computer picks random choice
LOGIC → RPS rules determine winner:
✅ Rock vs Scissors → You Win! (green msg)
✅ Paper vs Rock → You Win! (green msg)
❌ Paper vs Scissors → You Lost! (red msg)
➖ Rock vs Rock → Draw (navy msg)
SCORES → Update live display
REPEAT → Next round instantly!

## 📁 Full Project Structure
- index.html (3 choices + score board + msg container)
- game.css (dark theme + hover animations)
- game.js (complete RPS logic + scoring)
  images/ (rock.png, paper.png, scissor.png)

## 🎯 Sample Gameplay
You: Rock → AI: Paper 
→ "You lost! paper beats your rock" (RED)
Scores: You 0 | Computer 1

You: Scissors → AI: Paper  
→ "You win! Your scissors beats paper" (GREEN)
Scores: You 1 | Computer 

## 🔮 Future Features
- Best-of-10 with reset button

- Win streak counter

- Animated choice reveals

- Sound effects

- localStorage high scores

- Confetti on 5-win streak
