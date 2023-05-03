# Deploying an Angular Project using GitHub Pages

To deploy your Angular app using Github Pages, here's what you should do.

## 1. Create a Github Repository

   1. Go to your Github account on your browser.
   2. Click the "+" icon locator at the top-right of the page.
  
   ![image](https://user-images.githubusercontent.com/111161441/235946279-5015042f-0c8e-4cdf-8f8b-c3e3375b43f2.png)

   3. Select "New Repository".

![image](https://user-images.githubusercontent.com/111161441/235947379-80bce4ca-436c-4a42-b8ce-ab54684005e6.png)


## 2. Install the "angular-cli-ghpages" Package

   1. Open your Angular project directory in Visual Studio Code.
   2. Open the integrated terminal.
   3. Run the command using the integrated terminal:

      ```sh
      npm install -g angular-cli-ghpages
      ```

      >The "**npm**" command is used to interact with the Node Package Manager, "**install**" is a command used to install a package, "**-g**" is a flag that installs the package globally on the machine, and "**angular-cli-ghpages**" is the name of the package that will be installed.

## 3. Build The Angular Project

Run the command using the integrated terminal:

```sh
ng build --prod --base-href "https://username.github.io repositoryname/"
```

>The "**ng build**" command builds the Angular project for deployment, "**--prod**" is a flag that tells the Angular CLI to build a production version of the application, "**--base-href "https://username.github.io repositoryname/**" is a command wherein the Angular CLI will build a production version of the Angular project and set the base URL to the specified GitHub Pages URL.

## 4. Deploy the Project to GitHub Pages

Run the command using the integrated terminal:

```sh
npx angular-cli-ghpages --dir=dist/Project-name
```

>The "**ngh**" command deploys an Angular project to GitHub Pages using the "angular-cli-ghpages" package, the "**--dir dist/your-project-name**" is a flag that specifies the directory of the Angular project. Make sure to replace it with your project's actual name.

## 5. Visit the App Page

To visit the URL to your App gh-pages, access the URL **username.github.io**.

>Replace the username with your GitHub username.
