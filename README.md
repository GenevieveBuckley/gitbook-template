# MMI Training Material Gitbook Template
This repository hosts a template for MMI's training material gitbooks. The idea
is that this repo can be cloned and modified for new training books. It also
includes some basic instructions below for book contributors/editors, including
how to install the necessary requirements to edit books using the
[Gitbook editor](https://www.gitbook.com/editor).

## Using this template
If you haven't got `git` installed on your local machine and/or haven't signed up
for a Github account, please follow the setup 
[contributor/editor instructions](https://github.com/monashmicroimaging/gitbook-how-to-contribute).

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

You should now be able to follow the 
[contribution instructions](https://github.com/monashmicroimaging/gitbook-how-to-contribute) 
to edit the book with the Gitbook editor.


| ![](/assets/logos/logo_MMI.jpg) | ![](/assets/logos/logo_MHTP.jpg) | ![](/assets/logos/logo_hudson.jpg) |
| :---: | :---: | :---: |

