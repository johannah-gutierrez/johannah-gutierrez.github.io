# GitHub Push

## New Project

### 1. Clone the Repository from Remote (GitHub) to Local Repository

  1. Open your terminal or command prompt.
  2. Navigate to the directory where you want to store your project by using the cd command.
  3. Copy the URL of the GitHub repository you want to clone.
  4. In the terminal, enter the following code:

  ```sh
  git clone (URL)
  ```

  > Git will download a copy of the repository to your local machine. Replace the "**(URL)**" with the URL of your repository


### 2. Stage and Commit the Changes

  Staging and Commiting the Changes
  
   Open Visual Studio Code and navigate towards the Source Control tab found on the left menu bar.
  ![image](https://user-images.githubusercontent.com/111161441/236470027-d293d68d-42ec-463d-9e08-c9ad2fccc528.png)

  Click on the "**+**" sign or the stage changes button to the changes you will commmit.

  ![image](https://user-images.githubusercontent.com/111161441/236470470-92501389-7d38-4d3d-9021-2011514cd287.png)

  Once you click on the button, it will stage the change.

  ![image](https://user-images.githubusercontent.com/111161441/236470591-7c03a9de-3574-42bc-9fbc-e74beb27caf0.png)

  Commit the changes by either:
  
  - Entering a description on the text field above the commit button and pressing the "**Commit Button**" to commit the changes.
  
  ![image](https://user-images.githubusercontent.com/111161441/236471792-db2f7f47-127b-457f-997a-16c4acc5d4c6.png)

  - Pressing on the "**o**" button or the Conventional Commits button to commit the changes.
  
![image](https://user-images.githubusercontent.com/111161441/236472171-4ef01594-3da5-4115-8e8b-9d7a5bb1ebfa.png)


### 3. Push the Changes to Remote Repository (GitHub)

To push the changes from the local repository to the remote repository, enter the following code:

```sh
git push
```
## Existing Project

### 1. Initialize Git to your Local Project

  1. Open the terminal and navigate to the location of the project by using the "**cd**" command.
  2. Enter the following code to initialize a new Git Repository in the directory:
 
  ```sh
  git init
  ```
  
### 2. Set Remote Origin URL to your Remote Repository

1. On your remote repository (GitHub), navigate to the repository's page.

2. Click on the green "**Code**" button

![image](https://user-images.githubusercontent.com/111161441/236474612-8aa83faa-ea08-430e-9faf-a23fb98ac0a0.png)

3. Copy the URL that is under the HTTPS option.

![image](https://user-images.githubusercontent.com/111161441/236474953-82532d0f-baca-4ab5-8c8b-40ed1de55ec2.png)

4. Navigate to your Visual Studio and enter the following code:

   ```sh
   git remote add origin < URL >
   ```

   > Replace the "**< URL >**" with the URL copied from the previous step.

### 3. Set Remote Main Branch to your Local Main Branch

In the terminal in Visual Studio Code, enter the following code:

```sh
git push -u origin master
```

### 4. Stage and Commit the Changes

  Staging and Commiting the Changes
  
   Open Visual Studio Code and navigate towards the Source Control tab found on the left menu bar.
  ![image](https://user-images.githubusercontent.com/111161441/236470027-d293d68d-42ec-463d-9e08-c9ad2fccc528.png)

  Click on the "**+**" sign or the stage changes button to the changes you will commmit.

  ![image](https://user-images.githubusercontent.com/111161441/236470470-92501389-7d38-4d3d-9021-2011514cd287.png)

  Once you click on the button, it will stage the change.

  ![image](https://user-images.githubusercontent.com/111161441/236470591-7c03a9de-3574-42bc-9fbc-e74beb27caf0.png)

  Commit the changes by either:
  
  - Entering a description on the text field above the commit button and pressing the "**Commit Button**" to commit the changes.
  
  ![image](https://user-images.githubusercontent.com/111161441/236471792-db2f7f47-127b-457f-997a-16c4acc5d4c6.png)

  - Pressing on the "**o**" button or the Conventional Commits button to commit the changes.
  
![image](https://user-images.githubusercontent.com/111161441/236472171-4ef01594-3da5-4115-8e8b-9d7a5bb1ebfa.png)


### 5. Push the Changes from the Local to your Remote Repository (GitHub)

To push the changes from the local repository to the remote repository, enter the following code:

```sh
git push
```
