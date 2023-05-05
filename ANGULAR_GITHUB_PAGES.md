# Deploying an Angular Project using GitHub Pages

To deploy your Angular app using Github Pages, here's what you should do.

## 1. Create a Github Repository

   1. Go to your Github account on your browser.
   2. Click the "+" icon locator at the top-right of the page.
  
   ![image](https://user-images.githubusercontent.com/111161441/235946279-5015042f-0c8e-4cdf-8f8b-c3e3375b43f2.png)

   3. Select "New Repository".

![image](https://user-images.githubusercontent.com/111161441/235947379-80bce4ca-436c-4a42-b8ce-ab54684005e6.png)


## 2. Build The Angular Project

In this step, this Run the command using the integrated terminal:

```sh
ng build --output-path docs --base-href /repository-name/
```

>The "**ng build**" command builds the Angular project for deployment, "**--output-path docs**" is a flag specifies the output directory to 'docs' instead of the default 'dist', "**--base-href /repository-name/**" is a command wherein the Angular CLI will build a production version of the Angular project and set the base URL to the specified GitHub Pages URL.

## 3. Stage and Commit Changes

To stage and commit changes, here is what you will have to do.

  1. In Visual Studio Code, access the Source Control Tab located on the left menu bar.

![image](https://user-images.githubusercontent.com/111161441/236210609-da92dc4a-46fd-4d93-bccf-0436ba492eb0.png)

  2. Click on the "+" sign to stage the change.

![image](https://user-images.githubusercontent.com/111161441/236210879-017eec59-3904-4031-b26c-b4f2280140d5.png)

  3. Once the change is staged, click on the "o" or conventional commits button on the top menu bar of the source control panel.

![image](https://user-images.githubusercontent.com/111161441/236211369-671d5736-34f9-45e4-a2e8-fb2c8db6adae.png)

  4. A window will pop up. Select what kind of change is being commited, the scope, an emoji wherein it serves as a representative of what kind of change it is, and a comment to shortly describe the change commited.

![image](https://user-images.githubusercontent.com/111161441/236211478-1146cf0e-717f-44a5-b75d-1ff796efd145.png)

## 4. Push the Changes

To push the changes, there are two ways to push the changes.

- **Option 1**: Run the following code in terminal:

  ```sh
  ng push
  ```

- **Option 2**: Navigate to the Source Control tab found on the left menu bar of Visual Studio Code:
  
  ![image](https://user-images.githubusercontent.com/111161441/236364508-f441fdf7-1dc0-4fe8-a98c-4b9264f0e358.png)

  Press the "Sync Changes" button to push the changes.

  ![image](https://user-images.githubusercontent.com/111161441/236364362-b6a608f1-9e1b-4fde-ada9-c523ace07e1a.png)

  >If the button is not visible, make sure to commit any changes.

## 5. Deploy the Project to GitHub Pages

  1. Run the command using the integrated terminal:

  ```sh
  ngh --dir docs
  ```

  >The "**ngh**" command deploys an Angular project to GitHub Pages using the "angular-cli-ghpages" package, the "**--dir docs**" is a flag that specifies the directory of the Angular project. Make sure to replace it with your project's actual name.

  2. In your repository on GitHub, go to the "Settings" tab.

  ![image](https://user-images.githubusercontent.com/111161441/236138664-a14a025e-7642-4bbc-8860-a2bd0710a915.png)

  3. Scroll down to the "GitHub Pages" section.

  ![image](https://user-images.githubusercontent.com/111161441/236139154-0eceee9b-5f10-406c-ac1b-476ee19aee7d.png)

  4. In the "Source" section, select the "main" branch and the "docs" folder as the root directory for your GitHub Pages site.

  ![image](https://user-images.githubusercontent.com/111161441/236139415-4d1b6e1c-bd29-4689-9729-99b4b2d5214a.png)

## 6. Visit the App Page

To visit the URL to your App gh-pages, access the URL **username.github.io**.

>Replace the username with your GitHub username.
