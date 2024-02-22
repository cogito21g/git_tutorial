# Git Tutorial

## Make Environment
1. Install Git
  (Windows)
    1) Install Git on Website
  (Mac OS)
    1) Install XCode     (recommand)
    2) brew install git
    3) Install Git on Website

2. Sign Up GitHub
  1) Access the [Site](https://github.com)
  2) Enter the Email, Password

3. Make Remote Repository
  1) Sign in Github
  2) Click Repositories Tab
  3) Click New Button
  4) Fill the Template
    - Repository name: 
    - Description:
    - Public / Private
    - Uncheck Add a README file
  5) Click Create Repository Button

4. Git Setting(.gitconfig file)
  1) git config --list                              // show git settings
  2) git config --global user.name "username"       // set user name 
  3) git config --global user.email "email"         // set user email 
  4) git config --global -e                         // editor mode
  5) git config --global core.editor "code --wait:  // connect editor
  6) git config --global core.autocrlf input        // if (windows) true else if (mac os) input
  7) git config --global alias.st status            // set shortcuts
  8) git config -h                                  // manual page

5. Make Local Repository
  1) Make Empty Directory: mkdir <directory_name>
  2) Enter the Folder: cd <directory_name>
  3) Make Git Folder(make .git folder): git init

6. Connect remote and local Repository
  1) git remote add <name> <remote repository url>
    - git remote add origin https://github.com/<username>/<repository_name>.git

7. Make .gitignore file
  1) check ignore directory or file
  2) make .gitignore file: touch .gitignore
  3) open .gitignore file: vim .gitignore
  4) write folder_name or file_name

8. 
