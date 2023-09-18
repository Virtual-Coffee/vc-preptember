# Contributing Guide

---

## 📢 Only PRs from existing Virtual Coffee members will be accepted.

---

Welcome to the contributing guide for Virtual Coffee's Preptember repo! Thank you so much for considering contributing to this repository 💙.

We take our [Code of Conduct](https://virtualcoffee.io/code-of-conduct/) very seriously, and all contributors must abide by it. Let’s treat each other with respect, and remember, we are all people who care and are trying. If you believe someone has violated the Code of Conduct, please fill out our [CoC Violation Form](https://virtualcoffee.io/report-coc-violation/), which you can do anonymously.

## New contributors

If you're new to open source, check out the resources below to help you familiarize yourself with open source:

- [Virtual Coffee's Guide to Open Source](https://virtualcoffee.io/resources/developer-resources/open-source)
- [Intro to Open Source with OpenSauced](https://intro.opensauced.pizza/#/)
- [Git and GitHub learning resources](https://docs.github.com/en/get-started/quickstart/git-and-github-learning-resources)
- [Git Guides](https://github.com/git-guides)

## Contribution type

There are two types of contributions to this repo:

1. 🌱 **Practicing Open Source** — Add your name, link to your GitHub profile, and your favorite coffee (or any other drink you like!) to the `preptember-participants.md` file.

2. 📃 **Repositories List** — Add the link to a repository(ies) you recommend for Hackoberfest to the `repositories-list.md` file _only_ after the repository meets our requirements — check our [repository checklist](https://virtualcoffee.io/resources/developer-resources/open-source/maintainer-guide#repository-checklist). You can always return and add more repositories here.

## Getting Started

We recommend you work on the changes in your local environment because most of the contribution process requires you to do so rather than directly on GitHub.

### 1. Fork this repository

Click the `fork` button at the top of the front page. <br>
Forking is a process to create a copy of this repository in your GitHub account. You always want to remember to fork a repository before cloning it.

### 2. Clone the repository in your local machine

Clone a repository means copying the remote repository into your local machine.

#### On GitHub

1. Click your profile picture on the right top.
2. Click "Your repositories".
3. Open the forked repo by clicking on it.
4. Click the green `<> Code` button.
5. Click the copy icon to copy the HTTPS URL.

#### On your local machine

1. In your terminal, run this command to create a copy of the forked repository in your local machine:

   ```bash
   git clone https_url
   ```

   Change the `https_url` with the HTTPS link that you've copied.

2. Navigate to the directory where your local repository lives.

   ```bash
   cd vc-preptember
   ```

Remember that you always want to work on and push your changes into the forked repository, not the original one.

### 3. Create a branch

A branch is an isolated environment to work on and save your changes. Later on, you will push this branch to the remote repository after you finish working on your changes.

Run the following command to create a branch:

```bash
git checkout -b working-branch-name
```

You can name the branch anything you want — for example, `alice-add-profile`.

### 4. Work on changes

#### 🌱 Practicing Open Source

1. Open the `preptember-participants.md` file in VSCode or another text editor you use.
2. Add yourself to the file in this format:

   ```markdown
   - [Your name](link to your GitHub profile) | your favorite coffee or drink
   ```

   For example:

   ```markdown
   - [User Name](https://github.com/username) | Expresso
   ```

#### 📃 Repositories List

1. Open the `repositories-list.md` file in VSCode or another text editor you use.
2. Add the repository(ies) that you recommend for Hacktoberfest. **Please make sure the repositories pass the [repository checklist](https://virtualcoffee.io/resources/developer-resources/open-source/maintainer-guide#repository-checklist) before you add them**.

   ```markdown
   - [Organization / Repository Name](link to the repository)
   ```

   For example:

   ```markdown
   - [Virtual Coffee / virtualcoffee.io](https://github.com/Virtual-Coffee/virtualcoffee.io)
   ```

### 5. Add your changes

After you finish working on your changes, you must add them first. Adding changes means moving them into the staging area, where they will be ready to be saved (committed).

Run this command in your terminal:

```bash
git add .
```

This command will add all files with changes to the staging area.

### 6. Commit your changes

Now, it's time to commit the changes. Committing changes means saving your changes.

Run the following command:

```bash
git commit -m "Your message"
```

Change `Your message` into your own message. For example:

```bash
git commit -m "Add Alice to Preptember participants"
```

💡 **Good to know**:

When you make changes in an existing file, you can add and commit them all together with this command:

```bash
git commit -am "Your message"
```

### 7. Push your changes

You want to push your changes to your remote (forked) repository. Run this command in your terminal:

```bash
git push -u origin your-branch-name
```

Change `your-branch-name` with the name of your working branch. For example:

```bash
git push -u origin alice-add-profile
```

### 8. Create a pull request (PR)

1. Go to your forked repository on GitHub. <br> To ensure you're on the forked repo, look at the repo name on the top left beside the GitHub logo. It should have your GitHub username in the beginning: `your-username / repository-name`.
2. Click the `Compare & pull request` green button on the top.
3. Fill in the pull request form.
4. Click the green `Create pull request` button on the bottom.

And that's it! Congratulations on your first contribution to this repo! 🎉

## Resolve merge conflicts

You might encounter merge conflicts. When you encounter merge conflicts, you need to resolve them before your pull request can be merged into the `main` branch to avoid collision.

Merge conflicts usually occur when changes are on the same line(s), in the same file(s), from 2 different branches. It is common to encounter merge conflicts when contributing to open source.

Resources about merge conflicts:

- Virtual Coffee's Git & GitHub 101 guide to [resolving merge conflicts](https://virtualcoffee.io/resources/developer-resources/open-source/git-101#resolve-merge-conflicts).
- [Resolving a merge conflict on GitHub](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-on-github).

You can always ask for help in the `#open-source` or `#help-and-pairing` channel in Slack. We're here to help you 💙!

**Note**:

- We recommend resolving the merge conflicts in your local environment rather than directly on GitHub.
- For this contribution, we recommend you _accept both changes_.

## Awaiting Review

Once you've submitted your pull request, the only thing left is to wait for feedback from one of the project maintainers. Since this is volunteer work for all, if it's been over **one week** and you have not received any acknowledgment, you can post a comment on your pull request reminding you of its status.

## Suggested Changes

We may ask for changes before a pull request can be merged using [suggested changes](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/incorporating-feedback-in-your-pull-request) or pull request comments.

As you update your pull request and apply changes, mark each conversation as [resolved](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/commenting-on-a-pull-request#resolving-conversations).
