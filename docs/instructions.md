---
layout: tabbed-assignment
---

# Instructions

1. Start by using the **File Explorer** to create a folder called **GitHub** on your **Desktop**. Then, open that folder and create a folder called **{{site.data.assignment.local-path}}**. We will use this folder when we _clone_ the repository holding our starter code from GitHub.
1. The first time you clone with GitHub Desktop on a computer you will need to edit the Git configuration. Otherwise our firewall will trip you up.
   - Right-click in **File Explorer** and choose **Git Bash Here** from the context menu.
   - A terminal window will open running the **Bash** shell (a shell is a program that executes commands that you type).
   - In Git Bash type this command:

      ```bash
      git config --global http.sslverify false
      ```
   - Proofread and if it is right, hit the **Enter** key to run the command. If you need to make changes you can use the arrow keys to move around and edit what you typed.
   - Any output from the command indicates an error – most likely a typo, proofread again. You can use the up arrow key to move back through your command history.
1. Next, in your borowser, click on the link to go to the starter code repository on GitHub **[{{site.data.assignment.starter-code-org}}/{{site.data.assignment.starter-code-repo}}][starter-code-url].** When you get there find the **Fork** button at click on it to your own copy of the code.
1. To work with your fork of the **{{site.data.assignment.starter-code-repo}}** repository in Unity, you will need a copy on your computer. Git calls this step _cloning_. Start by finding the green **Clone or Download** button.
1. Click on the **Clone or Download** button and select the **Open in Desktop** option.
   - Since you probably haven't used GitHub Desktop on this computer before, this will take you to the GitHub Desktop download page.
   - Go ahead and download the Windows 64-bit version.
   - After GitHub Desktop downloads double-click on the dowloaded file in the lower left corner of your browser window.
   - Run the installer.
   - GitHub Desktop does not install globally (for all users), this is why you can install it. But this also means that you will have to do this anytime you are using a new computer.
1. GitHub Desktop will launch.
1. Sign in to your GitHub account.
1. Under **Your Repositories** select **{{site.data.assignment.starter-code-repo}}**.
1. For the **Local Path,** click on the **Choose** button and navigate to the folder you created is step 1 (e.g., C:\Users\<your login name>\Desktop\GitHub\{{site.data.assignment.local-path}}). 

   The reason it is ok to accept the default is that you are going to be pushing your changes to GitHub regularly. So the risk if losing work on the C: drive is reduced. In exchange you will get better performance from Unity.
1. Click on the blue **Clone** button and GitHub Desktop will copy the repository to your computer.
1. Finally, make a branch named **step-1** – having a common naming pattern for our branches will make it easier to talk about where we are in the project.

All that is left is to submit your work. Follow the instructions on the **Submission** tab to do that.

<!-- Don't edit links here, change them in _data/assignment.yml instead, -->

[slides]: <{{site.data.assignment.slides}}>
[starter-code-url]: <{{site.data.assignment.starter-code-url}}>
[template]: <{{site.data.assignment.template}}>
