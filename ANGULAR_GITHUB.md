# Deploying Your Angular App to Github

To deploy your Angular app using Github, here's what you should do.

## 1. Create a Github Repository

   1. Go to your Github account on your browser.
   2. Click the "+" icon locator at the top-right of the page.
   3. Select "New Repository".

## 2. Initialize Git in your project directory.

   1. Open your Angular project directory in Visual Studio Code.
   2. Open the integrated terminal.
   3. Run the command using the integrated terminal:

      ```sh
      git init
      git add .
      git commit -m "Initial Commit"
      ```

      > The "**git init**" command initializes a new Git repository in the directory, "**git add .**" command adds all the files to the curerent directory to the staging area, and the "**git commit -m "initial Commit"**" creates a new commit with all the changes that are in the staging area, and the "**-m**" specifies a message that usually contains the message that briefly describes the changes made in this commit.

## 3. Add a remote repository

Run the following command to connect your local repository to the remote repository that is on GitHub:

```sh
git remote add origin https://github.com/username/repositoryname.git
```

>Replace the username with your GitHub username and the repositoryname.git with the name of the repository you have created. The "**git remote add**" command adds a new remote repository to the local Git repository

## 4. Push the code to Github

To push the code to GitHub, run the command:

```sh
git push -u origin master
```

>The "**git push**" command pushes the changes in the local repository to the remote repository, the "**-u**" is a flag that sets the upstream branch for the current branch being pushed, the "**origin**" specifies the name of the remote repository and in this case, it is named 'origin' as it is a common convention for the primary remote repository, the "**origin**" specifies the name of the remote repository, and the "**master**" specifies the branch being pushed.
