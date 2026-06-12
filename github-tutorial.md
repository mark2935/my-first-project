### Part 1: What _is_ GitHub?

Imagine GitHub as **Google Docs on steroids**.

- **Git** is a "version control system." Think of it as a magical time machine. It takes a snapshot of your files every time you save them, allowing you to go back in time if you make a mistake.
- **GitHub** is simply a website that hosts those files and lets you collaborate with others.

**The Core Vocabulary (Keep this handy!)**

- **Repository (Repo):** A project folder. It holds all your files, images, and documents for a specific project.
- **Commit:** A "super save." When you commit, you are taking a snapshot of your work at that exact moment.
- **Branch:** A parallel universe. It lets you create a safe space to experiment with changes without ruining the original file.
- **Pull Request (PR):** Asking for permission to merge your experiment (branch) back into the main project.
- **Merge:** Combining your approved changes into the main project.
- **Clone:** Copying a remote repository to your local computer.
---

### Part 2: Your First Steps

#### Step 1: Create an Account

1. Go to [GitHub.com](https://github.com/).
2. Click **Sign up** in the top right corner.
3. Follow the prompts to create your account (you just need an email and a password).

#### Step 2: Create Your First Repository (Project Folder)

Let’s make a folder to hold our work.

1. Once logged in, look for the green **Create repository** button (or the **+** icon in the top right corner, then click **New repository**).
2. **Repository name:** Type `my-first-project`.
3. **Description:** Type "Learning how to use GitHub!"
4. **Public/Private:** Leave it on **Public** (anyone can see it, but only you can edit it).
5. Check the box that says **Add a README file**. (A README is just an instruction manual for your project).
6. Click the green **Create repository** button.

_Congratulations! You just made your first repo._

---

### Part 3: Making Changes and "Committing" Them

Now, let's edit that README file we just created.

1. You should be looking at your new repository. Click the pencil icon ✏️ next to the `README.md` file to edit it.
2. The file probably just says `# my-first-project`. Hit enter and type: `"Hello world! This is my very first GitHub edit."`
3. Now, we need to save this. In GitHub, saving is called **Committing**.
4. Look at the top right of the editing box and click the green **Commit changes...** button.
5. A small box will pop up. It will ask for a "Commit message" (a brief note about what you changed). It might say _Update README.md_ by default. That's perfect.
6. Click the green **Commit changes** button.

_You just made your first commit! You've taken a snapshot of your project._

---

### Part 4: Branching out (Experimenting Safely)

Let's say you want to write a new paragraph, but you aren't sure if you want to keep it. You can create a **Branch** to test it out.

1. Go back to the main page of your repository (click the name `my-first-project` at the top left).
2. Above your files, you’ll see a button that says **main** with a tiny branching icon. Click it.
3. A menu will drop down. Type a new name, like `draft-ideas`.
4. Click **Create branch: draft-ideas from 'main'**.
5. Notice that the button now says **draft-ideas** instead of **main**. You are now in your safe parallel universe!

**Make a change in your branch:**

1. Click the pencil icon ✏️ on the `README.md` file again.
2. Add a new line of text: `"Testing out some new ideas in my branch!"`
3. Click **Commit changes...**, leave the default message, and click **Commit changes** again.

_You have now saved this text in your `draft-ideas` branch, but the `main` branch is untouched._

---

### Part 5: The Pull Request (Bringing it all together)

Now, let's pretend you loved your new idea and want to add it to your official `main` project. You do this with a **Pull Request**.

1. Click on the **Pull requests** tab at the top of your repository page.
2. Click the green **New pull request** button.
3. You will see a lot of information, but look for the drop-down menus that say `compare: main`. Change `main` to `draft-ideas`.
4. GitHub will show you in green the text you added. Click the green **Create pull request** button.
5. Give it a title (like "Adding new ideas") and click the green **Create pull request** button one more time.

_You have just proposed a change! In the real world, this is where your teammates would review your work and say, "Looks great!"_

### Part 6: Merging

The final step is to accept the proposal and merge your parallel universe back into the main timeline.

1. On the Pull Request page you are currently on, scroll down and look for the green **Merge pull request** button. Click it.
2. Click **Confirm merge**.
3. You will see a purple box that says "Pull request successfully merged and closed."
4. (Optional) You can click **Delete branch** because you no longer need the parallel universe—your changes are officially part of the main project!

---

### 🎉 You Did It!

If you click the `<> Code` tab at the very top left to go back to your main repository page, you will see your `README.md` file now contains all the text you wrote.

**Review of what you just accomplished:**

1. Created a **Repository** (a project folder).
2. Made a **Commit** (saved a snapshot).
3. Created a **Branch** (a safe space to edit).
4. Opened a **Pull Request** (proposed your edits).
5. **Merged** your changes (made them official).