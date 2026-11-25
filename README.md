# 🏏 Cricket Tournament Management System

A console-based **Cricket Tournament Management System** developed using the C programming language. This project manages two cricket teams, tracks player performance, calculates ratings, updates player runs, and determines the Man of the Match based on performance.

---

## 📖 About the Project

The Cricket Tournament Management System is a menu-driven application designed to manage player statistics for two cricket teams.

The system allows users to view team information, update player runs, identify the youngest player, find the highest-rated players, and determine the Man of the Match. It also features a simple login authentication system and uses file handling to manage team data and player ratings.

---

## ✨ Features

- 🔐 **Login Authentication** – Secure access through username and password verification.
- 👥 **Team Information** – Displays complete statistics of both teams.
- ✏️ **Run Update** – Update a player's runs during the tournament.
- 🧒 **Youngest Player** – Find the youngest player from a selected team.
- ⭐ **Highest-Rated Player** – Identify the top-rated player of each team.
- 🏆 **Man of the Match** – Compare the highest-rated players from both teams to determine the winner.
- 📁 **File Handling** – Read team and login information from files and store rating data.

---

## 🧮 Player Rating System

Each player's rating is calculated based on the number of runs scored and wickets taken.

### Wicket Points

Each wicket contributes **8 points**.

### Run Points

| Runs Scored | Points |
|:---:|:---:|
| More than 75 | 24 |
| More than 50 | 20 |
| 20–50 | 12 |
| Below 20 | 4 |

### Rating Formula

**Total Rating = (Wickets × 8) + Run Points**

### Example

A player scores **60 runs** and takes **3 wickets**:

- Wicket Points = 3 × 8 = 24
- Run Points = 20
- **Total Rating = 44**

---

## 🎮 Menu Options

| Option | Description |
|:---:|---|
| 1 | Display Team 1 Information |
| 2 | Display Team 2 Information |
| 3 | Update Player Runs |
| 4 | Display Youngest Player Information |
| 5 | Display Most Rated Player of Team 1 |
| 6 | Display Most Rated Player of Team 2 |
| 7 | Determine Man of the Match |
| Q | Exit the Program |

---

## 🛠️ Technologies Used

- **Language:** C
- **Compiler:** GCC
- **IDE:** Code::Blocks
- **Libraries:** `stdio.h`, `stdlib.h`, `string.h`

---

## 🚀 How to Run

### Compile

```bash
gcc main.c -o cricket
```

### Run

**Windows:**

```bash
cricket.exe
```

**Linux/macOS:**

```bash
./cricket
```

> Make sure the required input files (`LogIn.txt`, `Team1.txt`, and `Team2.txt`) are available in the working directory before running the program.

---

## 🎯 Learning Objectives

This project helped us develop practical knowledge of:

- Structures (`struct`) for organizing player data.
- Arrays of structures for managing team members.
- Functions and modular programming.
- File handling in C.
- String manipulation and comparison.
- Conditional statements and loops.
- Basic authentication logic.
- Problem-solving through a real-world sports-based application.

---

## 👨‍💻 Contributors

**A.S.M. ABSARUZZAMAN**  
Student ID: `0112330445`
---

<p align="center">
  Developed with ❤️ using C
</p>
