## Step 4: Clean and analyse the data using R

For each of our two tasks, we will follow the same workflow, which takes advantage of the project management features (issues) and collaborative features (collaborators) of GitHub.

- Go to GitHub Desktop, and [create a new branch](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/making-changes-in-a-branch/managing-branches#creating-a-branch). Give it a name associated with the issue, for example data-cleaning (for issue 1) or data-analysis (for issue 2). Using a separate [branch](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches) allows you to isolate development work without affecting other branches in the repository.

- GitHub Desktop will then suggest that you [publish your branch](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/making-changes-in-a-branch/managing-branches#publishing-a-branch). This will make the branch available on the "remote" repository on GitHub.

- Next, GitHub Desktop will suggest that you create a [pull request](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests) from the current branch. This is how your changes will eventually be merged into the main branch of the repository (after you have finished your code development, and your code has been reviewed and approved by your collaborators). However, you haven't actually made any changes, so you can't create a pull request yet... We'll come back to that a bit later.

- Go to RStudio and open data-cleaning.Rmd (if you are working on issue 1) or data-analysis.Rmd (issue 2). Start working through the code.

- When you start making changes, remember to go back to GitHub Desktop frequently, to commit your changes. Make sure you commit the changes to the correct branch, and use good commit messages that briefly describe the changes you made.

- Every time you make a commit, GitHub Desktop will suggest that you "push" your commits to the "remote". This will make the changes available on the repository on GitHub. You do not have to push after every commit, but remember to do it before you finish working for the day, as this ensures your work exists on GitHub and not just on your local computer (so you won't lose all your hard work if your computer catches fire).

- At some point early in your code development, take up the offer from GitHub Desktop to [create a pull request](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request). (It will suggest this after every "push"). This will take you to the GitHub "Open a pull request" page.

    - Make sure that the [base branch](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request#changing-the-branch-range-and-destination-repository) (the branch you are proposing to merge the changes into) is the main branch of your forked repository, and not the original AbdnCHDS/open-research-how-to.
    - Change the "pull request" to "draft pull request". This tells your collaborators that your code is not yet ready to be reviewed.
    - Add "closes #[issue number]" in the description. This [links the pull request to the issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword). It shows that work is in progress to address the issue, and it automatically closes the issue when the pull request is merged.


- When you are ready to get feedback from your collaborators, [change the draft pull request to ready to review](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/changing-the-stage-of-a-pull-request#marking-a-pull-request-as-ready-for-review). Ask your collaborators to review your changes.

- When you get approval from the reviewers, merge the pull request and delete the branch (this closes the issue). It doesn't matter who merges the pull request (you or the reviewer), but successfully merging your changes is a satisfying action, so we recommend that you do it yourself - you've earned it after all your hard work. Well done!!

---
[GitHub Glossary](https://github.com/AbdnCHDS/open-research-how-to/blob/main/github-glossary.md)
