# Memory-Master
Memory Match Game
A responsive memory card matching game built with React, TypeScript, and Tailwind CSS.

Features:
1.Interactive card flipping animations.
2.Match detection with visual feedback.
3.Game state tracking (moves, matches).
4.Responsive design for mobile and desktop.
5.Victory modal when all pairs are found.

How to Play:
1.Click on any card to flip it and reveal the emoji.
2.Click on a second card to find a matching pair.
3.If the cards match, they'll stay face up.
4.If they don't match, they'll flip back after a short delay.
5.Keep flipping pairs until all matches are found.
6.Try to complete the game in as few moves as possible.
7.Setup and Installation.
8.Clone the repository.

Install dependencies:
1.npm install
2.Run the development server:
3.npm run dev
4.Open your browser to the displayed URL (typically http://localhost:5000)
5.Technology Stack
6.React
7.TypeScript
8.Tailwind CSS
9.Vite
10.Shadcn UI Components
11.Game Logic

The game uses a custom React hook (useMemoryGame) to handle the game state and logic:
1.Cards are shuffled randomly at the start of each game
2.When two cards are flipped, they're checked for a match
3.Matches are tracked, and the game completes when all pairs are found
4.A move counter keeps track of how many attempts the player has made
Enjoy the game!
