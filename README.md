# Better First Contributions

Learn how to contribute to Open Source without the fear of failure - like elsewhere you may have tried.

This project aims to simplify and guide the way beginners make their first contribution even more than previously thought possible.

If you are looking to make your first contribution, follow the steps below.

#### If you don't have git on your machine, [install it](https://help.github.com/articles/set-up-git/)

---

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account

<img src="https://www.betterfirstcontributions.com/fork.png" alt="fork this repository" />

---

## Clone the repository

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon

<img  src="https://www.betterfirstcontributions.com/clone.png" alt="copy URL to clipboard" />

Open a terminal and run the following git command - without the brackets:

```
git clone <url you just copied>
```

For example:

```
git clone https://github.com/<your-username>/better-first-contributions.git
```

---

## Create a branch

Open a terminal in or navigate to the repository directory on your computer (if you are not already there):

```
cd better-first-contributions
```

Now create a branch using the `git checkout` command:

```
git checkout -b your-new-branch-name
```

For example:

```
git checkout -b add-gin-tonic
```

The name of the branch does not need to have the word _add_ in it, but it's good practice to make comments more readable for other developers

---

## Create you file and commit changes

Now open `/Your Files My Children/` folder in a code editor, and create a new file inside it, with the extension of your choice.

---

## !!! New File Requirements !!!

- The file must be named exactly the same as your username!!! This is to ensure there is only one merge per GitHub user <br>
  Example: If your username is Solo, your file can be called Solo.ts or Solo.py etc.
- Create a file and make no other changes. Your pull request will not be accepted if you make more than one changes
- The file must be empty! Don't write anything at all in the file

---

Now, save the file.

---

If you go to the project directory and execute the command:

```
git status
```

you'll see there are changes

Add those changes to the branch you just created using the `git add` command:

```
git add .
```

Now commit those changes using the `git commit` command:

```
git commit -m "Add <your-file-name> to files folder"
```

replacing `<your-name>` with your name

---

## Push changes to GitHub

Push your changes using the command `git push`:

```
git push origin <your-branch-name>
```

replacing `<your-branch-name>` with the name of the branch you created earlier. If you don't remember what that is, there's a bit of homework for you - go find it!

---

## Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

<img  src="https://www.betterfirstcontributions.com/compPull.png" alt="create a pull request" />

Now submit the pull request.

<img  src="https://www.betterfirstcontributions.com/createPR.png" alt="submit pull request" />

---

## Merge your pull request NOW on our website!

Visit [our website](https://www.betterfirstcontributions.com/), login using your github account and merge the request right away!<br>
Want to know more about this project? Watch the YouTube video!(coming soon)

---

## Where to go from here?

Congrats! You just completed the standard _fork -> clone -> edit -> pull request_ workflow that you'll encounter often as a contributor!<br>
Want a biscuit?
