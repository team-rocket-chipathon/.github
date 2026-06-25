# About Team Rocket

Team Rocket is a global team participating in the 2026 IEEE SSCS "PICO" Chipathon. Our goal is to build hardware useful for implementing fully homomorphic post-quantim cryptographic systems.

Our entry for the Chipathon is a physical true random number generator suitable for post-quantum cryptosystem. This is a small part of the work we intend to do; eventually we want to build an AXI-stream coprocessor for accelerating the TFHE cryptosystem.

# Contributing

To contribute hardware or software code, follow the steps below. These steps are heavily based on the [GitHub flow](https://docs.github.com/en/get-started/using-github/github-flow).

### 1. Choose an open Issue

You can browse issues on our [progress tracker](https://github.com/orgs/team-rocket-chipathon/projects/2), or view them on the [issue tab of a repository](https://github.com/team-rocket-chipathon/lattice-coprocessor/issues). It's generally good practice to choose an issue that hasn't been assigned to someone. If you're viewing issues on a progress tracker, you should choose issues in the "Ready" or "Backlog" columns.

### 2. Clone the relevant repository

Find the repository where you plan to work on your selected issue and clone it. For example, if I were working on the [lattice-coprocessor repository](https://github.com/team-rocket-chipathon/lattice-coprocessor), I would clone it to my computer with the commands.

```
# Copy the repository from GitHub (remote) to my computer (local)
git clone https://github.com/team-rocket-chipathon/lattice-coprocessor/
```

> [!NOTE]
> If you aren't a member of Team Rocket, you can absolutely still contribute to our work! You'll just need to [fork the repository](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo) before starting work. By cloning your own fork, you'll be able to push your changes back up to GitHub.

### 3. Create a branch to work in

Create a new [branch](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches) with a name relevant to the issue you're working on. For example, if I had picked an issue titled "Design frobnosticator" I might use the commands below to create and switch to my branch.

```
# Navigate into the cloned repository folder
cd lattice-coprocessor
# Create a new branch to work on my issue
git checkout -b design-frobnosticator
```

> [!NOTE]
> GitHub provides an excellent [introduction to `git` commands here](https://docs.github.com/en/get-started/using-git/about-git#github-and-the-command-line).

### 4. Make your changes

This is the fun part! On your branch, you can safely modify code, add new tests, update documents, and make whatever other changes you please. However, keep in mind that someone will have to review your changes. If you make a lot of changes to unrelated files, it will be harder for team members to review your work. Keep your changes small and specific to solving your issue if possible.

Once you've made some changes, you'll need to package them up into a [commit](https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits). It's considered good practice to make several small commits instead of one large commit. Once you've made one or more commits, you should [push](https://docs.github.com/en/get-started/using-git/pushing-commits-to-a-remote-repository) it up to your GitHub remote.

> [!NOTE]
> Commit messages should start with a terse present-tense summary of the changes. After the first line, you should describe the changes with as much detail as is relevant. This is a great place to explain your motivations for a change too.

If you have questions about your work, make a comment on the issue you selected. You can also open a [Draft Pull Request](https://github.blog/news-insights/product-news/introducing-draft-pull-requests/) to discuss your changes earlier and include team members in your development process. This often makes it more likely that your work will be merged.

### 5. Open a Pull Request

Once your changes are complete, you should open a new [Pull Request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) (or PR for short). Most PRs won't be accepted until your changes are documented and well-tested, but it's often good practice to open them early (or better, open a Draft PR) so that relevant team members can see what you're working on. You can [open a pull request by following these instructions](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request#creating-the-pull-request).

After you open your PR, reviewers will begin to leave comments on your work. These will often be suggestions for improvements or questions about why you implemented things in a particular way. This is a collaborative back-and-forth process which will likely result in several rounds of changes and improvements to your work. If all goes well, your changes will be merged into the repository. 
