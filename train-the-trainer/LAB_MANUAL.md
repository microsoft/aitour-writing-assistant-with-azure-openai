### Welcome to the AI Tour and workshop WRK551!

In this session, you will learn how to build the app, **Contoso Creative Writer**. This app will assist the marketing team at Contoso Outdoors in creating trendy, well-researched articles to promote the company’s products.

### Pre-Requisites

To participate in this workshop, you will need:

1. Your own laptop.
   * It need only be capable of running a browser and GitHub Codespaces, so almost any laptop will do.
   * A recent version of Edge, Chrome or Safari is recommended.
2. A GitHub Account.
   * If you don't have one, you can [signup for a free account](https://github.com/signup) now.
   * After this workshop is complete, you will have a fork of the "contoso-creative-writer" repository in your GitHub account, which includes all the materials you will need to reproduce this workshop at home.
3. Familiarity with Visual Studio Code. 
   * We will run all code in GitHub Codespaces, a virtualized Linux machine, instead of your local laptop. We won't be running anything on your laptop directly.
   * VS Code Online will be our development environment in GitHub Codespaces.
   * If you are familiar with running Codespaces within VS Code Desktop on your laptop, feel free to do so. 
4. (preferred) Familiarity with the *bash* shell. 
    * We'll be using *bash* to run commands in the VS Code terminal.

### To begin this lab follow these steps:

1. You should currently be reading this from the **Instructions** tab and should see a login page besides it. You will *not* need to login to that page during this session.

2. You should also be able to see a **Resources** tab next to the Instructions tab. Click on it and in this tab you should do the following:

    * Confirm that you can see details for an Azure account including:
        * URL 
        * Subscription number
        * Username 
        * password
        
        Copy and save these somewhere you can easily access them!
    
    * Download your **.env file**. 
        * The Azure resources that you need for this workshop have already been provisioned, however to access them you will need environment variables stored in a .env file.
        * Click [this link](env download file) to download this file to your machine. You will copy the information in this file to a file named .env in the project repository shortly.  

    * Click **Open in New Window** at the bottom of the screen. This will direct you to a new window using a broswer on your own desktop. 

3. In the **newly opened window** navigate to this link [https://aka.ms/aitour/wrk551](https://aka.ms/aitour/wrk551). This will take you to the project Github repository. 
    * **Sign in** to GitHub if you aren't logged in already, using your own GitHub account credentials.

4. On the top right of the screen you should see a **Fork** button. Click that button and then click **Create Fork**. 
    * You should now be at the page *https://github.com/YOURUSERNAME/contoso-creative-writer* within your own GitHub account.

    * You now have a copy (known as a fork) of this workshop repository in your own GitHub account! Feel free to play with it, you won't break anything.

5. Click the green **<> Code** button in the top-right part of the page, click the **Codespaces** tab, and then click **Create codespace on main**.
    * This step takes a few minutes. The instructor will give you an overview of the session, and then you can begin work on your own in the Codespaces environment in your browser when it's ready.

6. Once your Codespace environment is ready:
    * Find the **docs** folder and in it open on the **workshop** folder. 
    * Find and open the **.env** file in the workshop folder and copy and paste the contents of your downloaded .env file in there. 
    * Copy and paste the following command in the terminal and press enter. 
    `.env --> .env` 
    * Now click the **README.md** file in the workshop folder and follow the instructions to get going! Have fun building!🎉