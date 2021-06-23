# LetsGitStarted
This repository serves as a playground for people who wish to learn version control using Git and GitHub.

Please make note of the following instructions:
1. There are none 😛

We don't care if you break things here. This is a playground which will make you familiar with popular git workflow. Use this for your practice.

## How to get started?
1. Go through the resources that we have shared on the WhatsApp group. There are countless resources available on the internet so you can refer anything that you're comfortable with.

2. On the [GitHub page for this repository](https://github.com/IEEE-SB-VIT-PUNE/LetsGitStarted), click on the Button "Fork". 

   ![fork image](https://help.github.com/assets/images/help/repository/fork_button.jpg)

3. Clone _your forked repository_ to your computer:

   ![code ui](https://docs.github.com/assets/images/help/repository/code-button.png)

    For example, run this command inside your terminal:

    ```bash
    git clone https://github.com/<your-github-username>/start-here-guidelines.git
    ```

    **Replace \<your-github-username\>!**

4. Before you make any changes, [keep your fork in sync](https://www.freecodecamp.org/news/how-to-sync-your-fork-with-the-original-git-repository/) to avoid merge conflicts:

    ```bash
    git remote add upstream https://github.com/zero-to-mastery/start-here-guidelines.git
    git pull upstream master
    ```

    If you run into a **merge conflict**, you have to resolve the conflict. There are a lot of guides online, or you can try this one by [opensource.com](https://opensource.com/article/20/4/git-merge-conflict).

5. On your computer, open your text editor, and add your name to the `CONTRIBUTORS.md` file.

6. Add the changes with `git add`, `git commit` ([write a good commit message](https://chris.beams.io/posts/git-commit/), if possible):

    ```bash
    git add CONTRIBUTORS.md
    git commit -m "Add <your-github-username>"
    ```

    **Replace \<your-github-username\>!**

7. Push your changes _to your repository_:

    ```bash
    git push origin master
    ```
    or 
    ```bash
    git push origin main
    ```

8. Go to the GitHub page of _your fork_, and make a pull request:

    ![pull request image](https://help.github.com/assets/images/help/pull_requests/choose-base-and-compare-branches.png)

    Read more about pull requests on the [GitHub help pages](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

9. Wait until one of the maintainers merges your pull request. If there are any conflicts, you will get a notification.

Congrats on completing all the steps! You're good to go now.
