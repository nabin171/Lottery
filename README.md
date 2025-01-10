# Lottery

Welcome to the **Lottery Game **! This is a fun and interactive game built using React. The app simulates a lottery game where random items are selected, and you win if you land on a special item (🍒, 🍋, 🍌). If you land on 💥, you lose.

## Features

- A random selection of items such as fruits and special symbols.
- A win/loss condition based on the selected symbol.
- Real-time updates of the selected item with a dynamic visual indicator.
- A pause button to stop the random selection.

## Technologies Used

- **React**: For building the user interface and managing state.
- **NextUI**: For styling the components, especially the button.
- **JavaScript (ES6+)**: For implementing the game logic and random number generation.

## How to Use

1. **Run the App Locally**:
   - Clone the repository:  
     ```bash
     git clone https://github.com/your-username/lottery-game.git
     ```
   - Navigate to the project directory:
     ```bash
     cd lottery-game
     ```
   - Install the dependencies:
     ```bash
     npm install
     ```
   - Start the development server:
     ```bash
     npm run dev
     ```
   - Open your browser and go to [http://localhost:3000](http://localhost:3000) to play the game.

2. **Gameplay**:
   - When the page loads, random items from the `lotteryOptions` array will be selected in a loop.
   - The game will display either "Congrats you won" along with the selected item or "You lost" if the selected item is 💥.
   - Press the **Pause** button to stop the random selection.

## Code Structure

- **Lottery Component**:  
  The core logic of the app is in the `Lottery` component, which manages the state and updates the displayed item every 50 milliseconds. It uses the `useEffect` hook to trigger the random selection based on the current state.

- **App Styling**:  
  The app is styled using **Tailwind CSS** for utility-first classes and **NextUI** for the button. The selected items are displayed in a grid with dynamic colors to highlight the current item.

## Future Improvements

- Implement a **pause/resume** functionality to control the game.
- Add sound effects or animations to enhance the user experience.
- Add a scoring system or counter for the number of wins and losses.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Thanks to [NextUI](https://nextui.org/) for their beautiful UI components.
- Special thanks to React for making web development easy and fun!

