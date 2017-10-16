# MMI Training Material Gitbook Template
This repository hosts a template for MMI's training material gitbooks. The idea
is that this repo can be cloned and modified for new training books. It also
includes some basic instructions below for book contributors/editors, including
how to install the necessary requirements to edit books using the
[Gitbook editor](https://www.gitbook.com/editor).

## Using this template
If you haven't got `git` installed on your local machine and/or haven't signed up
for a Github account, please follow the first 2 contributor/editor instructions below.

1. Clone this repository to your local machine:
```
mkdir /path/to/code_folder
cd /path/to/code_folder
git clone https://github.com/monashmicroimaging/gitbook-template.git mybook
```
2. Create a [new GitHub repository](https://github.com/new) with your books
   name e.g. "mybook"
3. Update the remote origin of your local repository to the remote you've just
   created on GitHub.
```
cd mybook
git remote set-url origin git@github.com:username/mybook.git
```
Note: You should replace "username" with your or your organisations GitHub username.
4. Push the local template to the newly created GitHub repo:
```
git push origin master
```

You should now be able to follow the instructions below to edit the book with
the Gitbook editor.

## Instructions for training material contributors/editors
### 1. Get git installed on your machine
* Download git from: https://git-scm.com/downloads
* Install git using the install wizard.

### 2. Setup a GitHub account
* Create a free GitHub account at: https://github.com/join?source=header-home
* Ask one of the MMI Image Analysts to add you to the Monash Micro Imaging GitHub group: https://github.com/monashmicroimaging
    Email us and tell us your GitHub username so we can add you as a member.

### 3. Install the GiHub desktop app
* Download the GitHub desktop app for your operating system at: https://desktop.github.com/
* Install the GitHub desktop app using the install wizard.
* Note: The default path will be: ~\\Documents\\GitHub\\

### 4. Install the GitBook editor
* Download the GitBook editor at: https://www.gitbook.com/editor
* Install the Gitbook editor using the install wizard.
(Optional: You don't have to make an account on the GitBook website. The Gitbook editor will prompt you to sign up or login every time you open the editor, but you can just click 'No thanks' or 'Remind me later'.)
* Change the GitBook library path.
*(This step is so you get a nice list of all your Gitbooks when you open the Gitbook Editor.)*
  1. Create two sub-directories (folders) inside your GitHub folder.

    *You can make the new folders with Windows Explorer/Finder/Dolphin (Windows/Mac/Linux) or however you usually like to create folders.*
    * The first folder is called "Gitbook_library" and goes inside the folder named "GitHub", eg: ~\\Documents\\GitHub\\Gitbook_library\\
    * The second folder is called "Gitbooks" and goes inside the folder named "Gitbook_library", eg: ~\\Documents\\GitHub\\Gitbook_library\\Gitbooks\\

  1. Change the library path of the Gitbook Editor
    * Open the GitBook editor you just installed.
    * Click the GitBook editor menu, then click "Change Library Path..."
    * Set the Gitbook editor path to: ~\\Documents\\GitHub\\Gitbook_library\\

Done! You have everything installed now that you'll need to contribute to our Gitbooks.

## Get the Gitbooks (cloning from GitHub.com)
  * Go to the Monash Micro Imaging github page: https://github.com/monashmicroimaging
  * Find the Gitbook you want in the list of repositories, and click to open it (eg: gitbook-fiji-training).
  * Now click the green "Clone or download" button on the right hand side, then click "Open in Desktop".
Find the Gitbook you want, and clone it
https://help.github.com/desktop/guides/contributing-to-projects/cloning-a-repository-from-github-to-github-desktop/


## Contributing to a GitBook


### Check for any changes made by other people


## Further resources
## Generating eBooks and pdfs
https://toolchain.gitbook.com/ebook.html

### Markdown syntax guides
http://commonmark.org/help/
https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

### GitBook help
GitBook help centre website: https://help.gitbook.com/

### GitHub help
https://help.github.com/

### GitHub pages
https://pages.github.com/
https://help.github.com/articles/using-a-custom-domain-with-github-pages/
