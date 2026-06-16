# Tic-Tac-Toe
Tic-Tac-Toe is a simple two-player strategy game played on a 3x3 grid where players take turns marking spaces with 'X' and 'O'.  The objective is to be the first to form a horizontal, vertical, or diagonal line of three identical marks<br>
Coded Simple Tic-Tac-Toe as a Favorite Game of Childhood using HTML, CSS, JS.

---
<h1>HTML</h1> <br>
Simple HTML<br>

▪️9 Boxes-Buttons<br>
▪️Reset Button<br>
▪️NewGameButton<br>

---
<h1>CSS</h1><br>
Modern Color Palette with Buttons and Text Colors with Background.<br>
▪️Calling Classes<br>
▪️Calling ID<br>
▪️.hide<br>
▪️#msg<br>

---
<h1>JavaScript</h1><br>
Logical with functions such as:<br>
▪️winPatterns - Identifying all the patterns and all the conditions for the Winner.<br>
▪️showWinner-Msg for showing Winner with  disableBoxes(); .<br>
▪️checkWinner-For loop for the winPatterns.<br>
▪️newGameBtn-For New Game after Winner Announced.<br>
▪️resetBtn-For Reset in the Middle of the Game.<br>

```
for (let pattern of winPatterns) {
    let pos1Val = boxes[pattern[0]].innerText;
    let pos2Val = boxes[pattern[1]].innerText;
    let pos3Val = boxes[pattern[2]].innerText;

    if (pos1Val != "" && pos2Val != "" && pos3Val != "") {
      if (pos1Val === pos2Val && pos2Val === pos3Val) {
        showWinner(pos1Val);
      }
    }
  }
```

---
<h2>Win Patterns 🏆</h2><br>

```
const winPatterns = [
  [0, 1, 2],
  [0, 3, 6],
  [0, 4, 8],
  [1, 4, 7],
  [2, 5, 8],
  [2, 4, 6],
  [3, 4, 5],
  [6, 7, 8],
];
```



