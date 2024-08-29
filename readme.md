# Fortune Slot Game
Fortune Slot Game, a sample of H5 game.

## Introduction
The Fortune Slot Game is a slot machine, offering a 5-reel, 3-row setup with randomized spins. Players win by matching symbols on adjacent reels, starting from the left. The game features animated winning symbols, a customizable paytable, and a user-friendly interface. The project captures the essence of casino slots, providing a fun, engaging experience while serving as a foundation of development concepts.
#### Symbol & Payout Sumarry

| Symbol Name   | Symbol ID | Payout (3 Matches) | Payout (4 Matches) | Payout (5 Matches) |
|---------------|-----------|--------------------|--------------------|--------------------|
| **Diamond**   | 0         | 5.0                | 10.0               | 20.0               |
| **Red Gem**   | 1         | 4.0                | 8.0                | 16.0               |
| **Crown**     | 2         | 3.5                | 7.0                | 14.0               |
| **7 (Seven)** | 3         | 3.0                | 6.0                | 12.0               |
| **Clover**    | 4         | 2.5                | 5.0                | 10.0               |
| **Bell**      | 5         | 2.0                | 4.0                | 8.0                |
| **A**         | 6         | 1.5                | 3.0                | 6.0                |
| **J**         | 7         | 1.2                | 2.4                | 4.8                |
| **K**         | 8         | 1.0                | 2.0                | 4.0                |
| **9**         | 9         | 0.9                | 1.8                | 3.6                |
| **10**        | 10        | 0.8                | 1.6                | 3.2                |
| **Q**         | 11        | 0.7                | 1.4                | 2.8                |
| **M1**        | 12        | 0.6                | 1.2                | 2.4                |
| **M2**        | 13        | 0.5                | 1.0                | 2.0                |
| **M3**        | 14        | 0.5                | 1.0                | 2.0                |
| **M4**        | 15        | 0.4                | 0.8                | 1.6                |
| **M5**        | 16        | 0.4                | 0.8                | 1.6                |
| **M6**        | 17        | 0.3                | 0.6                | 1.2                |
| **Bonus**     | 18        | -                  | -                  | -                  |

### Prerequisites
- Required latest LTS Version: 20.11.0 (includes npm 10.2.4)

### Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/mail2ashutosh/fortuneslotgame.git
   
2. Execute below commands on the terminal:
- To install dependencies, run ```npm install```
- To create the build, run ```npm run build```
- To run the application, run ```npm run start```

### How to Use
- Load the game with GitHub page link or for local launch the url: http://localhost:7777/
- The game is designed to be played in full screen. If you resize your screen, please reload the page to ensure the game automatically adjusts to the current screen size.
- For detailed information about the game, please refer to the README.md file.
- Open Bugs - pending issues and fixes will be addressed, and the latest version of the game will be updated soon.

## Open Bugs
- Symbol animations with payout game flow related obvious issues.

## Future Scope
- Support of different winning state and toggle effect.
- Win tick-up for winning amount.

## Change Logs

### 1.0.0 (2024-08-12)
#### [Added]
- Fixing bugs related to game winning round & investigated.
- Game polishing and code refactored.
- Updated the README file, managed game repo.

### 0.0.5 (2024-08-10)
#### [Added]
- Support symbol animations with payout calculations, integrated ways win RNG logic, and updated the code flow.
- Updated the README file with relevant details and a description of the symbols.
- Game polishing and code quality improvements.
- JSDoc comments added for each class and method to generates documentation automatically using tools.

### 0.0.4 (2024-08-09)
#### [Added]
- Added a click effect to the Spin button and updated the code flow.
- Enabled reel spinning by clicking the mouse button on the reel area.
- Managed the game state, user balance, and other elements after the reels stop.

### 0.0.3 (2024-08-08)
#### [Added]
- Integrated background assets, designed the game header, bottom bar, and Spin button using code.
- Managed UI components' resizing during fullscreen mode and on the first reload.

### 0.0.2 (2024-08-07)
#### [Added]
- Fixed common issues and implemented reel spinning mechanics.
- Handled the enable/disable functionality of the Spin button and refactored the code.

### 0.0.1 (2024-08-05)
#### [Added]
- Initial project setup with using typescript, pixi.js v6, webpack & webpack-cli and other dependencies.
- Project folder structure created for extensible use and enhancement purposes.
- Used build tool, configured webpack.config.ts
