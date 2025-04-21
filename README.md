# Maze Generator & Solver ️ labyrinth

**Dive into the captivating world of mazes!** This interactive JavaFX application isn't just a program – it's your personal Labyrinth Architect and Navigator. Generate complex puzzles, pit your wits against AI solvers, or simply enjoy the journey through winding digital corridors. Challenge yourself, explore classic algorithms in action, and have fun getting lost (and inevitably found!).

## Why Explore This Maze Project? 🤔

* **Learn by Doing:** A fantastic visual tool for understanding fundamental maze generation and pathfinding algorithms like Prim's, BFS, and DFS. See how they actually work!
* **Algorithm Showcase:** Directly compare how different algorithms create vastly different maze structures and solving paths.
* **Interactive Fun:** It's not just theoretical – generate a maze and jump right in to solve it yourself with keyboard controls.
* **Solid Foundation:** Built using JavaFX with the clean MVVM pattern, making it a good example of desktop application structure.

## What Can You Do? ✨ (The Fun Stuff!)

* **Become the Maze Architect:** Instantly generate unique mazes. Choose algorithms like Prim's to create complex, sprawling structures or use simpler methods for different styles. You control the blueprint!
* **Watch the AI Conquer:** Select algorithms like BFS, DFS, or Best-First Search and watch them visually carve out the solution path. See the shortest route (BFS) or the deep dives (DFS) in action.
* **Take Control & Navigate:** Guide your character using keyboard controls through the twists and turns. Can you find the exit faster than the AI? It's a race!
* **Customize Your Labyrinth:** Easily adjust the maze size (rows/columns). Create quick puzzles or epic, screen-filling challenges that truly test your navigation skills.
* **Save Your Masterpieces:** Designed a particularly tricky or beautiful maze? Save it to a file (it even uses compression!) and load it back anytime to revisit or challenge friends.
* **Smooth & Polished Experience:** Enjoy exploring with a clean, responsive interface built natively with JavaFX. Features like zooming and character selection enhance the interaction.
* **Tune the Atmosphere:** Adjust application settings and immerse yourself further with optional background music and sound effects.

## Maze Algorithms Inside 🧠 (The Brains of the Operation)

This application lets you experiment with different ways to create and solve these intricate puzzles:

**Maze Creation (Building the Walls):**

1.  **Randomized Prim's Algorithm:** Builds the maze like a growing tree, often resulting in many short branches and a complex, challenging structure. Great for exploration!
2.  **Simple Generator:** A more basic, often faster approach, useful for understanding core generation principles or creating simpler layouts.
    *(Add details on any others you have!)*

**Maze Solving (Finding the Way Out):**

1.  **Breadth-First Search (BFS):** Methodically explores level by level. **Guaranteed** to find the absolute shortest path in terms of steps – think ripples expanding outwards.
2.  **Depth-First Search (DFS):** Dives deep down one path before backtracking. Finds *a* path quickly, but it might be long and winding, not necessarily the shortest.
3.  **Best-First Search:** An "informed" search using heuristics (like distance to the goal). Often finds a path faster than BFS/DFS but doesn't guarantee the absolute shortest route – it takes educated guesses.

## Get Started 🚀 (Launching Your Adventure)

Ready to explore? Here’s how to get the application up and running:

**You'll Need:**

* **Java Development Kit (JDK):** Version X.X or higher recommended (*Specify exact version, e.g., JDK 17+*). Make sure it's installed and configured.
* **JavaFX SDK/Modules:** This is crucial for the UI. Depending on your JDK, it might be included, or you may need to download it separately and configure your environment/build tool to use it. (Common setup step: Ensure your IDE or command line knows where to find JavaFX modules).
* **(Build Tool):** Apache Maven / Gradle (*Specify which, if used*). This helps manage dependencies like JavaFX.

**Installation & Launch:**

1.  **Get the Code:** Clone or download this project repository.
    ```bash
    git clone <your-repository-url>
    cd <repository-directory>
    ```
2.  **Build it (Compile the Code):**
    * *Using Maven:* `mvn clean install`
    * *Using Gradle:* `gradle build`
    * *Using an IDE (like IntelliJ, Eclipse):* Import the project (as a Maven/Gradle project if applicable) and use the IDE's build action.
3.  **Run it! (Start the Application):**
    * *Using Maven (if javafx plugin configured):* `mvn javafx:run`
    * *From your IDE:* Locate the `Main.java` class (usually in `src/` or `src/main/java/...`) and run it directly.
    * *From the built JAR (example command - might need adjustment):*
        ```bash
        # You MUST tell Java where to find JavaFX modules if they aren't bundled
        java --module-path /path/to/your/javafx/sdk/lib --add-modules javafx.controls,javafx.fxml -jar target/your-app-name.jar
        ```
        *(Replace `/path/to/your/javafx/sdk/lib` and `your-app-name.jar` accordingly)*

## How to Play ▶️ (Basic Controls)

1.  **Launch** the application using one of the methods above.
2.  **Generate:** Find the 'New Maze' button or menu item. You might be asked for dimensions (rows/cols).
3.  **Solve:** Click 'Solve Maze' (or similar) to see the computer find the path.
4.  **Navigate:** Use **Arrow Keys** (or specify if WASD) to move your character from the start to the goal.
5.  **Save/Load:** Look for 'File' menu options to save your current maze or load a previously saved one.
6.  **Explore Menus:** Check out 'Properties', 'Help', and 'About' for settings and information.

---

Built with **Java** and **JavaFX**, utilizing the clean **MVVM pattern** for a well-organized and maintainable structure. Enjoy your maze adventures!
