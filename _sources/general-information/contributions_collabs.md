# Working Collaboratively

To demonstrate how you can work collaboratively using GitHub and Jupyter Book, we can perform a somewhat useful exercise. 

There are two ways to go about this: either you invite someone as a collaborator and give them access to your course repository, or via forking (link) a repository to create your own version, making changes and asking the original owner hwether they would like to accept your changes via a s- called "pull request". We will go through both options in detail below.


## 1. Adding Collaborators.

First, please, find a partner and invite each other as collaborators to your respective repos. This will allow you to have access to each other's repo and, given a specific role, you may modify the contents or structure of the repository.
You can do so by navigating to the settings -> collaborators page of your repo and simply selecting *Add people*.


![Image](../static/collaborators.png)


Search for people via their GitHub Username, Email, etc., and click *Add to repository*.

![Image](../static/search_people.png)


Now simply wait for them to accept your invite. 


#### Working with collaborators

As collaborators on private repositories have full access to the project and default have write access, you can simply select one of the files and start making changes or create new files for your contributions. 

Navigate to the "general information" folder of your partners repository. Click "Add file", give your contribution a name and make sure it ends with `.md` (so that GitHub knows we want a markdown formatted file). 

![Image](../static/create_file.png)


Now simply add a header, do so by declaring the first line of the document as the title via the use of a single hash, e.g. your title could be

```
# Notes and things
```

Note that everything behind the hashtag will be rendered as the title of the newly created webpage in the table of contents on your rendered website. To make these changes visible, we are still missing one final step, though. So add some notes or a friendly message to your partner and click "commit changes" in the upper right hand corner. 

In the commit view, add an informative title and describe the changes you have made in as much detail as necessary.

![Image](../static/committing.png)

To make the newly created content appear on the website, we have to add the new file to our `toc.yml`. Jump back into the [Creating OER tutorial](https://diler-digitell.github.io/didactic-jupyterbook-workshop/content/4_additional/quick_tutorial_ws.html) to recall how to do this.

Once you have committed the changes to the `toc.yml`, you can check the actions workflows and following, the course website to view your rendered contributions.

So congratulations, you now know how to leverage the central hub of the global software development economy to manage your own projects! You can now effectively declare that you are using the "gold standard" frameworks of the tech industry for collaborative coding and software project management.


#### Working with Branches: Ordered collabs

While editing files directly on the main page works, it comes with a risk. Imagine if you and your partner both try to rewrite the introduction chapter at the exact same time. Who wins? Usually, this will result in one of two things, either the last person to click "Commit" overwrites the other person's work, or GitHub declares a "merge conflict". Meaning that you will be asked to manually decide which version of the file you will want to keep.

To avoid this chaos, developers use `Branches`.

Think of the `main` branch (the one you are working on now, check screenshot) as the "published" version of your book. It should always be clean and error-free. 

![Image](../static/main_branch.png)

When you want to try a new idea, the standard should be to create a new "branch", i.e. making your own copy of the project at its current state and taking it to a separate room to implement some of your ideas. If you mess up or break something, you can just throw the copy away without changing the original files. If you like it, you "merge" it back in.

To learn more about branches and how this all works, you can look into this free visual learning tool: [learngitbranching](https://learngitbranching.js.org/)


### 2. Outside collaborators and Independent contributions: Forking & Pull Requests

What if you want to, e.g., contribute to a massive open-source textbook where you don't know the owners personally? Or you want to invite help from someone outside your core team, e.g., a student from another university or a subject matter expert, without giving them full "Write" access to your repository. Giving every single contributor direct access is risky as they could accidentally delete files, push unfinished drafts to your main branch, or create merge conflicts.

The safest way to contribute or accept contributions from people you don't fully trust or who you just want to help once) is by 'forking' the repository. We have already learned about this in the previous lesson, but for the sake of training, let's make some changes to a partner's repository and then ask them to review and accept those changes via a so-called "pull request".

#### The Forking Workflow

A "Fork" is simply a personal copy of your repository that lives under the contributor's account. They have full freedom to break, fix, or rewrite their copy without affecting your original project at all.

Navigate to your partner's repository. In the top right corner, look for the Fork button.


![Image](../static/fork_button.png)


Once you click it, GitHub opens a windows were you can select the speicfics of what you want to copy from the repository in question. Clicking `Create Fork` creates a clone of their repository under your username. You will see the title PartnerName/YourProjectName with a small label underneath: forked from PartnersName/PartnersProjectName.

![Image](../static/fork_view.png)


#### 2.2 Making Safe Changes

Now that you have your own forked version, you can freely edit files, create branches, and commit changes exactly as if it were your own project.

Now make a small improvement or leave a short message in one of the copied `.md files`. Notice that while you are doing this, their original repository remains completely unchanged. This is the safety forking provides. If you want to propose that these changes should be implemented in the original owners repository, you can do so via a `Pull request`. Find more info on this in the [GitHub Tutorial on Pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork).


