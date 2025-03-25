# 🏆 Team Score Calculator

This JavaScript program calculates the average scores of two teams, Dolphins and Koalas, and determines the winner based on a set condition. 🏀🐬🐨

## 🚀 Features
- Uses an arrow function to calculate the average score.
- Implements a function to check the winner based on the given conditions.
- Logs the result to the console.

## 📜 Code Overview
```javascript
const calcAverage = (par1, par2, par3) => (par1 + par2 + par3) / 3;

const scoreDolphins = calcAverage(44, 23, 71);
const scoreKoalas = calcAverage(65, 54, 49);

function checkWinner(avgDolphins, avgKoalas) {
    if (avgDolphins >= 2 * avgKoalas) {
        console.log(`Dolphins win (${avgDolphins} vs. ${avgKoalas})`);
    } else if (avgKoalas >= 2 * avgDolphins) {
        console.log(`Koalas win (${avgKoalas} vs. ${avgDolphins})`);
    } else {
        console.log("No team wins...");
    }
}
```

## 🛠️ How to Use
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/team-score-calculator.git
   ```
2. Open `script.js` in your favorite code editor.
3. Run the script in the browser console or Node.js.

## 📢 Output Example
```
No team wins...
```

## 📌 Notes
- The winner is determined when a team's average score is at least **double** the opponent's average.
- If no team meets this condition, no winner is declared.

## 🎯 Future Enhancements
- ✅ Accept user input for dynamic scores.
- ✅ Implement a web-based interface to visualize results.
- ✅ Add more teams for competition.

## 📜 Created by
This project was created by **Sky**. ✨

## 📜 License
This project is open-source and available under the MIT License.

---

⭐ Feel free to contribute, fork, or give a star! 🌟
