# Class Directory

This repository will contain our class directory, which will be created by all of you. To contribute your information to the directory, you will:

1. Fork this repository
2. Clone your fork of the repository on your computer
3. Create a new branch for your changes
4. Add your information to the directory.md file
5. Commit your changes to your local repository
6. Push your changes up to your Github account
7. Create a Pull Request on Github

# Step by Step

Here are the details to complete each step

<details id=1>
<summary><h3>Step 1: Fork this repository</h3></summary>

This is easy. Just click on the **Fork** button at the top of this repository page. This will create a fork under your account.

</details>

<details id=2>
<summary><h3>Step 2: Clone your fork to your computer</h3></summary>

This will create a copy of your forked repository on your computer. To do this:

![image](https://raw.githubusercontent.com/Newaygo-County-CTC-IT/class-directory/main/images/2-clone-1.png)

1. On your repository, click the green Code button.
2. If **SSH** is not selected, click on it.
3. Click on the copy button.
4. Open a terminal on your computer, and type `git clone ` and then paste the repository code you copied. <br>
   ![image](https://raw.githubusercontent.com/Newaygo-County-CTC-IT/class-directory/main/images/2-clone-2.png)
5. Press <kbd>Enter</kbd> and let `git` download the repository.
6. Enter the directory by executing `cd class-directory`.

</details>

<details id=3>
<summary><h3>Step 3. Create a new branch for your changes</h3></summary>

When you are in the repository directory run the command (except replace *mr-baldus* with your name)

```bash
git checkout -b adds-mr-baldus
```

It is important to **ALWAYS** do your local work in a branch that is named after what it is doing.

</details>

<details id=4>
<summary><h3>Step 4. Add your information to the directory.md file</h3></summary>

The easiest way to edit the directory.md file is to just open it with Visual Studio Code. Type 

```bash
code directory.md
```

Then you need to add a section for yourself. Make sure there is a blank line before your section. Each section should look like this:

```markdown
## Mr. Baldus

* email: jason.baldus@gmail.com
* github: jbaldus
* ssh-key: ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIO5DTtzsrVzumPE4vjE3SXgGJ3FyoolVMRSh3Fqo3l2z jason.baldus@gmail.com

---

```

Then save the file with <kbd>ctrl</kbd>+<kbd>S</kbd>.

Hint: This command will copy your ssh key to your keyboard so you can paste it in here: `xclip -sel clip < ~/.ssh/id_ed25519.pub`.

</details>

<details id=5>
<summary><h3>Step 5. Commit your changes to your local repository</h3></summary>

Run the git command below to commit your changes to your local repository, but change the *Mr. Baldus* to your name

```bash
git commit -am "Adds Mr. Baldus to directory.md"
```
</details>

<details id=6>
<summary><h3>Step 6. Push your changes up to your Github account</h3></summary>

Run the git command below to push your changes to a branch on Github that matches the branch you made on your local machine. Change the *mr-baldus* part to be your name.

```bash
git push --set-upstream origin adds-mr-baldus
```

Now, if you go back to your Github repository, you will see a notification that your branch had a recent push. 
</details>

<details id=7>
<summary><h3>Step 7. Create a Pull Request on Github</h3></summary>

To request that your changes be incorporated back into the original project, we create a *Pull Request*, which tells the owner of the original project that you have some changes you think would help out. We already have a notification inviting us to create a pull request, so go ahead and click on the green **Compare & pull request** button.

![image](https://raw.githubusercontent.com/Newaygo-County-CTC-IT/class-directory/main/images/7-create-pr-1.png)

This opens up a page that allows you to explain your changes. For this *PR*, just explain that your change *Adds Mr. Baldus to the directory*, or something similar. Then click the green **Create Pull Request** button

![image](https://raw.githubusercontent.com/Newaygo-County-CTC-IT/class-directory/main/images/7-create-pr-2.png)

This will notify Mr. Baldus that you have made a change that you would like to see added to the project, and give him the ability to *merge* your change into the project. He might need to ask you to make some changes first, and that is what the discussion about the *PR* is for.

</details>

<details id=X>
<summary><h3>Finish</h3></summary>

Congratulations! You have completed the process of submitting a Pull Request!

Here's what you have done today:

- You forked a repository
- You created a local clone of that repository
- You created a new branch to contain your work
- You pushed your changes to your repsitory
- You created a Pull Request

</details>
