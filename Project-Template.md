# Guidelines
### All Projects
* Each member should be assigned at least one component or task as agreed upon by the group, separate from all other components and members
* A component is a part of the project that will require development to complete, this could be a feature or a core part of the program.
* Those who complete their component can be assigned another component as agreed upon by the group.
* Questions should go to the project lead, then to the project committee member, then to one of the VPs of Engineering.

### Basic Projects
* Should have user input via command line
* Needs to use functions (or subroutines)
* Should use an array or list structure to store data, and choose which one based on appropriateness

### Intermediate Projects
* Project should be a desktop or web application with appropriate UI
* All error cases should be handled appropriately 
* Advanced data structures should be used (where needed) to make application more efficient and they should be optimal if possible

### Advanced Projects
* They need to use concurrency (threads)
* Space and time complexity should be manageable (max O(nlogn) time complexity)
* Should do data processing (for example parsing a csv, or querying a database)
* Should also satisfy the intermediate project requirements

# Ideas and Examples
Below are some examples of projects that could be designed in a way to cover any difficulty. I provide a couple examples of "dressing" a project up or down based on skill level too. Most projects can be dressed up or down, but some are more suited for a particular skill level.

## Games
Games are fun and can be motiviating to work on because of that.
### Chess
I personally love chess, and I have made it about 4 times now. It is a lot of fun to do and I have found it is a great benchmark for testing my own skills.

Example Core Components
* **Input / Output (incl. display)**
* **Moves, Pieces, Check, Checkmate**
* **Players, turns - playing the game**
* **Special Moves (En pessant, castling, pawn promotion)**
* Stalemate

Additional Components
* Highlighting playable moves (UI versions)
* Save Games
* Move Timer (tournament style)
* Multiple Game Modes
   * 4x4 chess
   * tournament (timed standard)
   * speed chess
* Online play
* Enemy AI (single player mode)
* Puzzles

### Uno
Make the family classic, or a spinoff with the "illegal plays" - stacking should be official. With games like this, it is an advantage to know who has what cards, so input / ouput should consider this and work around it.

Example Core Components
* **Input / Output (incl. display)**
* **Valid card plays, deck, shuffle**
* **Point system**
* **Special cards (wild, draw 2, skip, etc.)**

Additional Components
* Save Games
* Highlighting playable cards (UI versions)
* Lowscores (given a certain number of games played), or Highscores if you want to embarass your friends
* Alternative rule sets - zeros swap cards, that sort of thing. Can make it a separate game mode.
* Enemy AI
* Online play

### Other Games
* Wave Game ([Great tutorial](https://www.youtube.com/watch?v=1gir2R7G9ws&list=PLWms45O3n--6TvZmtFHaCWRZwEqnz2MHa) showing game development fundamentals. It is slightly outdated though).
* Tower Defense

## Business
### Task Manager (Calendar etc.)

Example Core Components
* **Persistently delete, add, edit, and complete tasks**
* **Input / Output**
* **Efficiently display tasks in a calendar format i.e. sorted (UI or otherwise)**

Additional Components
* Descriptions, links, subjects, other sub data for tasks
* Reminders (set for certain times)
* Sounds - probably linked to reminders
* Preferences
* Help (how to use program)
* Online storage / sync with login
* Repeating tasks

### Integrated Development Enviroment (IDE)

Example Core Components
* **Text Editor (edit & save files)**
* **Filesystem Mangaer**
* **Compiler** (run the languages compiler, output results, not create your own)
* **UI**

Additional Components
* Syntax Highlighting
* GitHub interface
* Debugger
* Vim or Emacs emulation etc.

### Site Mockup
Take one of your favorite sites, and do your best to replicate functionality / look and feel. Best to pick a site that has functionality.
A great example is making a Trello (board) site.
