# Git Basic Notes

### 23 Jan 2022 (Sun) - Git Identification
1. In order for Git community to know where the commits, pull requests, and so on are coming from, you must tell Git your name and email address by running the commands below:
git config --global user.email "you@example.com"
git config --global user.name "Your Name"

1.1 This will set your account's default identity.
1,2 Omit --global to set the identity only in this repository.

### 23 Jan 2022 (Sun) - Git Team Glossary and Use of BRANCHES
1. It's good for a team of collaborators to develop their own GIT glossary to enable smooth communication.
2. A BRANCH is a full copy of the MASTER BRANCH that you can work on INDEPENDENTLY without affecting the MASTER BRANCH.
3. In a BRANCH you can add new commits, new features, new folders, new images if it's a WORKING DIRECTORY for creating a website for example, new code in general, and so on, and then add this as a first commit, second commit, and so on commit.
4. Once your done with all your CHANGES IN YIOUR BRANCH, you can add these changes back to the MASTER BRANCH. 
5. Adding your changes in your BRANCH to the MASTER BRANCH is called MERGE.
6. Great benefit of GIT is that we can add features or any improvements (through the use of BRANCHES) in the RUNNING VERSION OF THE PROJECT, which is the MASTER BRANCH.  CLEARLY, GIT ALLOWS FOR THE AGILE SCRUM APPROACH OF PROJECT MANAGEMENT!!!
7. We can refer to BRANCHES as basically SUB FOLDERS INSIDE A GIT PROJECT, wHERE EACH COLLABORATOR IS WORKING INDEPENDENTLY ON DIFFERENT PARTS OF THE PROJECT, WITHOUT HAVING AN IMPACT ON THE ACTUAL RUNNING VERSION OF THE PROJECT.

### 23 Jan 2022 (Sun) - Git Installation Using MacOS Terminal
1. There are many ways to install GIT in macOS as listed below:
1.1 Homebrew - by using the command "brew install git"
1.1.1 But first download and install Homebrew from the URL https://brew.sh
1.2 After installing GIT through the the command "brew install git" at your terminal, type the command "git --version" to check whether GIT was successfully installed and to find out whether you have the latest version installed.
1.2.1 The latest version of GIT is indicate at the Apple Monitor at this URL https://git-scm.com
1.3 n case, it's not showing the latest GIT version, simply exit the terminal and open another terminal, which may do the trick. 

2. Xcode and many more, but I recommend Homebrew.

### 23 Jan 2022 (Sun) - Visual Studio Code Installation in MacOS
1. Since the example project in the tutorial is to create a website, we will install the Integrated Development Environment (IDE) VISUAL SUDIO CODE.
2. VISUAL CODE STUDIO is free, commonly, and widely used IDE platform.
3. Take note that VISUAL CODE STUDIO is a CROSS PLATFORM, which means that it works for both windows and macOS
4. To download and install the VUSUAL CODE STUDIO, go to this url  https://code.visualstudio.com/
5. After downloading VISUAL CODE STUDIO, double click the downloaded file.
6. Then, a security notification will pop up stating that "Visual Studio Code can't be opened because it was not downloaded from the App Store. Your security preferences allow installation of only apps from the App Store."
6.1 There is a workaround for this to allow the installation of Visual Studio Code. Follow the below steps:
6.1.1 Click the Apple icon at the uppen left corner of your screen and select "System Preferences ..." to open the System Preferences page.
6.1.2 In the System Preferences page, double click "Security & Privacy" to ope the Security & Privacy page.
6.1.3 In the Security & Privacy page, go to the "General" tab. 
6.1.4 In the General tab page, you'll see a not at the left of the "Open Anyway" button stating ""Visual Studio Code" was blocked from use because it is not from an identified developer." 
6.1.5 You'll also see in this "General"tab that "App Store" is selected for "Allow apps downloaded from:" 
6.1.5.1 To change the "App Store" selection to "App Store and Identified developers", click the podlock icon found at the bottom left corner of this page to unlock it and enable you to make the change on setting.
6.1.6 After unlocking the padlock icon to lock it, select "App Store and Identified developers" and click the "Open Anyway" button.
6.1.7 Then, click again the padlock icon to lock it.
6.1.8 Finally, go back to the VISUAL STUDIO CODE to open the dowloaded file and install it. This time, you should be able to install it! 
  
### 23 Jan 2022 (Sun) - How to Delete a .DS_Store file Using the MacOS Terminal
1. In the Terminal type the command "rm -v **/.DS_Store"

2. Learn more about the file ".DS_Store" in this URL https://buildthis.com/ds_store-files-and-why-you-should-know-about-them/
3. We must delete this file. Refer to the excerpts below:
3.1 A .DS_Store, short for Desktop Services Store, is an invisible file on the macOS operating system that gets automatically created anytime you look into a folder with ‘Finder.’ This file will then follow the folder everywhere it goes, including when archived, like in ‘ZIP.’
3.2 If you’re a developer or system administrator and still transferring files from your computer to your server or don’t take the necessary precautions with your automated deployment process, you could be putting these files on the server where your site or application lives unconsciously.
3.3 The people who want to prevent security breaches through .DS_Store files are developers and system administrators. Finding .DS_Store files in random folders in your server is not fun. You could be leaking information you don’t intend to. If you do find one, simply delete the file with the command  ‘rm .DS_Store’ and it will be resolved.
3.4 The easiest way to prevent this problem from happening is to completely turn off the automatic creation of these files. Follow the steps in the URL https://buildthis.com/ds_store-files-and-why-you-should-know-about-them/
3.5 For developers, you can use Git to solve this problem by doing the following:
3.5.1 Place .DS_Store in your .gitignore file. 
3.5.2 That way, any .DS_Store file will be ignored and not be pushed with the rest of your code.




