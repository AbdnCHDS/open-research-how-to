## Step 2: Create an RStudio project

It is important to keep all files associated with a project together and well organised, which is why we have developed a recommended folder structure. If the project is an R project, we can go one step further and create an [RStudio project](https://support.rstudio.com/hc/en-us/articles/200526207-Using-Projects) from it. This creates an .Rproj file and sets the R working directory to the directory the .Rproj file is located in. The advantages of this will become clearer when we start working with R code.

To create an RStudio project, start RStudio, and click on "New Project...", either via the Project or the File menu. Select "Existing Directory" and navigate to the location of this project on your computer.

If you now look at the project directory, you will see that it contains a new file, open-research-how-to.Rproj.

Let's [commit this change](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/making-changes-in-a-branch/committing-and-reviewing-changes-to-your-project):

- Go to GitHub Desktop, and make sure the "Current Repository" is open-research-how-to. It should show the new .Rproj file under "Changes".
- In "Summary", write a short message describing the change, for example: "Created RStudio Project"
- Click "Commit to main". This will commit the change to the main branch of the repository.

When we start working on our tasks, we will create dedicated branches to develop our code. We will only request for our changes to be pulled into the main branch when we have completed our code and it has been reviewed by our collaborators. This ensures that the main branch always contains code that is complete and approved. We will talk more about this in [step 4](04-data-cleaning-analysis.md). Creating an RStudio project is a small change that does not need to be approved by our collaborators, so we can commit it to the main branch directly.

- Click "Push origin". This will push the change from your local computer to the "remote" repository, which is your repository on GitHub.   

Excellent! You are now ready for [step 3: adding collaborators and tasks](03-collaborators-tasks.md).

---
[GitHub Glossary](github-glossary.md)
[Main Readme Page](readme.md)
