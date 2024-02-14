**Text Adventure Game - Documentation:**

This Java program implements a text-based adventure game named "Mystical Forest Adventure." The game presents a narrative-driven experience where the player makes choices, encounters challenges, and engages in a quest. Below is a brief documentation of the design and features of the code:

1. **Game Initialization:**
   - The game begins with a welcome message, introducing the player to the Mystical Forest Adventure.
   - The player starts at the entrance of a mystical forest with two initial paths.

2. **Player Choices:**
   - Players make choices by entering numeric options prompted by the game.
   - The choices determine the progression of the story, leading to different scenarios and outcomes.

3. **Paths and Encounters:**
   - The game offers two paths: "Go left" and "Go right."
   - Each path involves unique encounters, such as a talking owl, a magical river, and a creature to fight.

4. **Treasure and Scoring:**
   - If the player chooses the correct path, they may find a hidden treasure, earning a score increase.
   - The score is cumulative and contributes to the final score at the end of the game.

5. **Mystical Village:**
   - If the player finds the treasure, they explore a mystical village with a wise elder.
   - Interaction with the elder introduces a quest to retrieve a magical artifact to save the forest.

6. **Quest and Negotiation:**
   - Players can choose to fight or negotiate with a mystical creature guarding the artifact during the quest.
   - Negotiating successfully adds a substantial score bonus.

7. **Combat System:**
   - The game features a turn-based combat system when the player chooses to fight.
   - The player and the creature take turns making choices (attack or defend) until one side is defeated.

8. **Attack Moves:**
   - Three attack moves are available: Quick Strike, Power Slash, and Fireball.
   - Each move has a random damage value, adding variability to the combat experience.

9. **Defense Mechanism:**
   - Players can choose to defend during combat, reducing the damage taken from the creature.

10. **Game End and Stats Display:**
    - The game ends when the player successfully completes the quest or is defeated in battle.
    - Final stats, including the player's score and health at the end of the adventure, are displayed.

11. **Input Validation:**
    - The program validates user inputs, ensuring that only valid choices are accepted.
    - Invalid inputs lead to an error message and the termination of the game.

12. **Randomization:**
    - Random values are used for various aspects of the game, such as attack moves' damage and the creature's attack.

13. **Termination:**
    - The game terminates gracefully using `System.exit(0)` after displaying the final stats.

14. **Code Structure:**
    - The code is organized into methods, each responsible for handling specific parts of the game flow.
    - The modular design enhances readability and maintainability.

15. **User Interaction:**
    - A `Scanner` object is used to capture user input, facilitating interaction with the game.

Overall, the code creates an engaging text adventure game with a mix of exploration, decision-making, and strategic combat. Players navigate through a mystical forest, encountering challenges and ultimately aiming to save the forest by completing a quest. The modular design and thoughtful features contribute to an immersive gaming experience.
