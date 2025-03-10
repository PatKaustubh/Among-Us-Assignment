# 🎮 Among Us Data Analysis Assignment

## 📌 Overview
Among Us is a multiplayer social deduction game where players are assigned roles as Crewmates or Impostors. The goal is either to complete tasks (Crewmates) or eliminate other players without being detected (Impostors). This assignment involves analyzing game data using MongoDB to extract insights and structure the data for predictive and descriptive analysis.

---

## 🛠️ Tasks & Queries

### 1️⃣ **Reading the Data **
- Use the `mongoimport` command with `--jsonArray` to load the dataset into MongoDB.
- Query to display data for the game with `game = "3"`.

### 2️⃣ **Exploring Game 3 **
- Create a new collection containing only the document related to game 3.
- Display the **Game Feed** data for game 3.
- Identify and display the **last event** in game 3.
- Determine the winner (Crewmates or Impostors) based on the final event.
- Identify the player who picked the **black color** and their role.
- Count the number of **voting events** in game 3.
- **Database Redesign Suggestion**: Explain how the structure could be optimized for easier querying.

### 3️⃣ **Overall Aggregation **
- Count the total number of **events** across all games.
- Count the number of games won by **Crewmates vs. Impostors**.
- Find the number of games played on each **map**.
- Calculate how many times **the Crew skipped a vote**.
- Count the number of times **Crew voted against Impostors**.
- Provide insights: Is the game harder for **Impostors or Crewmates**? Justify with data.

### 4️⃣ **Player-Level Aggregation **
- Find the number of **unique players** in the dataset.
- Identify the **best Crewmate** (who voted out Impostors the most).
- Identify the **worst Crewmate** (who voted out Crewmates the most).
- (Optional) Calculate **win percentage** for each player.
- (Optional) Identify **color preference** for each player.
- (Optional) Export structured data in the following format:

| Player Name | Games Won as Impostor | Games Won as Crew | Win Percentage | Voted Against Impostors | Voted Against Crew | Color Preference | Voting Rate |
|------------|---------------------|-----------------|---------------|--------------------|-----------------|----------------|------------|

### 📊 **Further Analysis**
- Suggest additional **player statistics** for a better selection process.

---

## 💾 **Downloadable Data Links**
- [📂 Among Us Data](https://drive.google.com/file/d/19VTCzoJzJYBw5xIunG8VOvax45bYsjwO/view?usp=sharing)


## 🚀 **Next Steps**
- Load the data and start **exploring game 3**.
- Implement **aggregation queries** for overall and player-level insights.
- Document findings and structure the output.
