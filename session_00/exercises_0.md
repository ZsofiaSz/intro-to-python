# Session 0 Exercises

## Section A

Before you start, make sure that you are using the Shell 🐚 (not the console).

1. Use `pwd` to check in what directory you are.

2. Use `ls` to check what files and folders are in the current directory.

3. Using `cd <directory_name>` go into the "session_00" directory.

4. Create a new folder named "my_first_folder" using `mkdir <directory_name>`.

5. Delete the empty folder "my_first_folder" using `rmdir <directory_name>`.

6. Create a new folder named "animals" using `mkdir <directory_name>`.

7. Get into the animals folder by using `cd <directory_name>`.

8. Create 3 text files named "penguins.txt", "dogs.txt", "bees.txt" by using `touch <file_name.txt>`.
    - Extra challenge: Can you do this while using `touch` only once?

9. Create your first python file called "snakes.py" by using `touch <file_name.py>`.

10. Delete the bees.txt file with the `rm <file_name.txt>` command.

11. Display the text "I love cake" to to the terminal by using `echo <text>`.

12. Write the line "Whippet" in the dogs.txt file using `echo <text> > <file_name.txt>`.

13. Display the date in the terminal using the `date` command.

14. Display the recent history of your bash commands using the `history` command.

15. Clear your terminal with the `clear` command.


# Section B

1. Get out of the `animals` folder using `cd ..` .
2. Create a Markdown file called "my_markdown_recipe" using `touch <file_name.md>`.
3. Inside the "my_markdown_recipe.md" file,  type a recipe you like in Markdown format. If you don't have any ideas, and writing up in Markdown seems too much of a chore, just ask [ChatGPT](https://chat.openai.com/) to write one for you (Ex: "Write a burger recipe in markdown format."), and then paste it into your file. 
    - When you are done, click on the "open preview" option to see the formatted version.

Great job on getting so far, just one more section to go!

# Section C

1. Get out of the "session_00" folder using `cd ..` .
2. Make sure you are in the "intro_to_python" directory by using the `pwd` command.
3. Use `git status` to see what files and folders have been modified/c
3. Use the `git add .` command to stage all the work you have done.
4. Commit your work with `git commit -m`






---


## Cheat sheets
 - Command Line [cheat sheet](https://www.git-tower.com/blog/command-line-cheat-sheet/)
 - Git commands [cheat sheet](https://education.github.com/git-cheat-sheet-education.pdf)
- Markdown [cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) 

---

## Refresher

### Bash commands:

```bash
pwd # Prints to the console the path of your current working directory

ls # Lists the files in the directory you are in


cd <directory_name> # Gets in a given directory

cd .. # Gets out of the directory you are in



mkdir <directory_name> # Creates new directory

rmdir <directory_name> # Deletes an empty Directory (Folder)

rm -r <directory_name> # Deletes the directory and its contents recursively


touch <file_name.txt/file_name.py> # Creates new file

rm <file_name.txt/file_name.py> # Deletes file



echo <text> # Displays in the terminal a line of text, Ex: echo Hello!

echo <text> > <file_name.txt>  # Writes a line of text in a file, Ex: echo Bonjour! > file.txt

cat <file_name.txt> # Reads the file and displays it line by line in the terminal, Ex: cat file.txt --> Bonjour!


history  # Displays your recently run Bash Commands​

date # Displays the date

clear  # Clears the terminal screen

```

---

### Bash shortcuts:

- TAB - autocompletes commands, file names, or directory names for you​.

- UP/DOWN Arrows - Scroll backward and forwards through previous commands you’ve typed in the current session. ​

---

### Git commands:

```shell

git add . # Adds ALL changes to the staging area in preparation for committing them to the repository.​

git commit -m "<Short description of what you have worked on.>" #  Saves changes to the local repository, along with your commit message, usually describing the changes.

git push origin main # Uploads local changes to your remote repository, on the main branch.
```

---



