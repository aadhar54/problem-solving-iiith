What is Git Fork and Forking in Git?
A fork is a copy of a repository. Forking a repository allows to freely experiment with changes without affecting the original project.

Confused? let me try again. Forking in GitHub is a process of creating a copy of a complete repository to the user’s GitHub Account from another account. When a user forks a repository, all the files in the repository are automatically copied to the user’s account on GitHub and it feels like the user’s own repository. This process is similar to copying a folder from one drive to another drive in a computer. The user is then free to use this repository either for their purpose or experiment with changes in the code. Through git forking, the users can develop their own modifications to the code that belongs to someone else.

To be noted, that this process does not have any effect on the original repository (also called an upstream repository) code.

Git Fork - Fork a Repo

 

Git forking through GitHub is a process that is isolated to GitHub. This means that whenever a git fork happens, the repository and the code remains confined to the user’s GitHub account. There is no effect on the local machine of the user or the involvement of Git in the process.

 

Why Fork a Repository on GitHub?
Forking a GitHub repository provides an individual with the copy of the upstream repository to their account. But why would we need to fork a repository which is developed by someone else? The answer to this question is in the concept of GitHub itself. GitHub was developed to provide a platform to all the developers around the world so that they can contribute to each other’s project and make a better, more reliable software. It is obvious no one would want to see hundreds of changes without their consent on the original repository. Hence, the concept of a copy of the repository or a forked repository comes into the picture.

Forking a repository on GitHub is done for two main purposes:

Improving someone’s code/software: Improving someone’s code does not necessarily mean fixing the bugs and improving the execution time. Improving can be adding a new feature to the existing software/repository. For example, I navigate to a repository and liked the concept of the software. Now I have something else in mind that could be useful for the same software. I can fork the repository, develop the feature on my machine and send the changes to the owner of the repository.
Reusing the code in a project: A user can also make use of git fork to fork the repository of another user to use in their own project. The idea here is “why to reinvent the wheel”. The popularity of Git is also because people add their code, project, module, software, etc on GitHub as a public repository. Now other people are allowed to use that open source code to their project, which helps them to save their efforts and time. 
Note: Forking is allowed for public repositories without permission. But if the repository is private, one can only be able to fork if he or she has permission from the owner of the repository. 

 

How does Forking (Git Fork) work?
Git Fork is a simple process in GitHub and it does not require to use any git command. The process of Git Fork follows the below steps:

Fork a Repository: User creates a copy of the repository to their own GitHub account, the steps for the same are covered in the next section.
Code changes: This involves git cloning, which is the next chapter of the Git Tutorial series. But on a high level, the user makes the changes and push back to their own forked repository.
Send changes to Original Repository: This process is called as Pull Request in Git. At this step, the user sends the changes to the owner of the repository as a request. Now it is up to the owner to accept the changes or reject. Pull request is a request to the owner of the upstream repository to accept the user changes. 
1_Pull-Request

Alright then, I hope it is clear about the concept of forking a repository on GitHub. It is time we see how to do that.

 

 

Git Fork
In this section, we will see how to fork a GitHub repository. A user can fork any public repository and add it to their own account. But, for simplicity, we will be forking a small repository that I created on my another account.

 

How to Fork a Repository on GitHub?
To fork one of my repository on GitHub for practice, Login to your account.

Now, my account name (from which we will fork the repo) is harishrajora while the repository name is ToolsQA. You can use any one of the following parameter or both of them to search for the repository.

If you are using the name as a parameter, type the name in the search bar. Press All GitHub after entering the name to search everywhere in GitHub.

Git Forking Process - search_by_name_github

 

A message will appear telling there is no repository by this name.

Git Forking Process - Find a GIT repo to fork

 

This is because if you look at the left column of the page, Repositories is selected on that by default. Since there is no repository by the name harishrajora, it showed that message. We know that harishrajora is a user name, so, select Users in the list.

Git Forking Process - Select Users Search GitHub

 

The number in front of users denotes there are two users available by that name. Select the first one with the name harishrajora only.

Git Forking - list_of_users

 

If you are using the name+repository as the search parameter, then type the following in the search bar and press All GitHub.

search_by_name_repo

 

Continuing with the search by user name that we did first, once you choose a user, his profile will open up. The profile will show popular repositories. Select ToolsQA among the repositories.

ToolsQA_select_repo

 

Pressing ToolsQA will open up the repository page. You can also skip all the above steps and visit the repository page directly through this link. But, it is better to know how to navigate.

 

Press Fork button to initiate the git forking process.

Git Forking button on Github

 

The repository ToolsQA will be forked to your account instantly. This can be seen by your username after forking the repository.

forked_repo

Now that you have the copy of the repository using git fork, you can modify and improve the code according to yourself. There will also be cases when you would want to delete the forked repository. The next section will help you out in this regard.