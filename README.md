# Git Basics Game

Welcome to the Git Basics Game! This game is designed to help you learn the basics of Git while having fun. Follow the instructions below to complete the game.

## Instructions:

### Setup:
1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/zodicslanser/git-basics-game.git
   ```

2. Navigate into the cloned repository.
   ```bash
   cd git-basics-game
   ```

3. Create a new branch with your name.
   ```bash
   git checkout -b your-name
   ```

### Game Rules:
- Each step will have a specific task related to Git.
- Follow the instructions carefully to complete the task.
- If you get stuck, feel free to ask for help or refer to Git documentation.

### Tasks:
1. **Commit Your Name:**
   - Open the `players.txt` file.
   - Add your name to the list.
   - Save the file and close it.
   - Commit your changes with a meaningful message.
     ```bash
     git add players.txt
     git commit -m "Add [Your Name]"
     ```

2. **Create a New File:**
   - Create a new file named `[Your Name].txt` (replace `[Your Name]` with your actual name).
   - Add some text to the file.
   - Save the file.
   - Add and commit the new file.
     ```bash
     touch [Your Name].txt
     # Open the file in a text editor and add some text
     git add [Your Name].txt
     git commit -m "Add [Your Name].txt"
     ```

3. **Merge Your Changes:**
   - Switch back to the main branch.
     ```bash
     git checkout main
     ```

   - Merge your branch into the main branch.
     ```bash
     git merge your-name
     ```

4. **Push Your Changes:**
   - Push the changes to the remote repository.
     ```bash
     git push origin main
     ```

### Game Over:
Congratulations! You've completed the Git Basics Game. You've learned how to commit changes, create branches, merge branches, and push changes to a remote repository using Git.

Feel free to explore more Git commands and experiment with branching strategies. Happy coding!

---

Feel free to customize the game instructions and tasks according to your project's needs. This game provides a hands-on approach for beginners to learn Git basics while interacting with a real repository.
