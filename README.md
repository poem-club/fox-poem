# fox-poem

This is a repository(repo) for workshop: Intro to Git & Github.
The repo takes a poem as the example to explain the git and github concepts.

## markdown language
- `# header`
- `## header2`
- just type = paragraph
- `- ` = list
- `**BoldText**` = **BoldText**
- `*italics*` = *italics*
- link: `[poem repo](https://github.com/poem-club/fox-poem/)` = [poem repo](https://github.com/poem-club/fox-poem/)
- more reference: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

## Git, Github, Repo, Commits
- Git is a version control tool
- Github is a website where you can do projects that have version control on them.
- Repository: You can create repository. A GitHub repository is another word for a project. It can have multiple files associated with it.
- Commits: 
  - You can make changes to those files by making commits.
  - the commits allow you to browse the history on the project timeline
  - each commit has a unique identifier called hash

## Branch
- When you create a Github repository, the main linear list of commits, the history, is on the **main branch**.
- You can create a **branch** if you want to have an experimental try but don't want to change on the original version.
- You can create a new branch on one branch.
- For collaborative project, a repo could have a set of branches while people working on different aspects of the same document.
- You can see a **visual graph** under the tab "insights", in "Network". 
- Note: Making a banch may seem tricky and similar to making commits on the main branch. But branching is really making a more substantive, a substantial commitment to the idea of a separate path.

## Merge a branch back into the main
- You can make a **pull request** and merge your branch into the main branch.
- A pull request takes some changes from a particular branch and bring them into another branch.
- Github will check for us if there is conflict between branches.

## Fork
- You can **fork** a repo from another account's repo.
- You can have the entire repo with the histories in your account and make your changes on it.
- If you want to contribute to the original repository, you can send your edition to the original repo as a **pull request**. It's up to the original repo's creator to accept/reject that pull request.

--------------

## Reference
- Markdown Cheatsheet: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
- Install Git(Preparation for next workshop)
  - Mac: Most versions of MacOS will already have Git installed. Check Terminal with `git version`.
  - Windows: Download the Git Bash https://git-scm.com/downloads
  - More on https://github.com/git-guides/install-git

Great thanks to UAL CCI, Phoenix Perry, Mick Grierson, and Dan Shiffman for the encouragements and support.
