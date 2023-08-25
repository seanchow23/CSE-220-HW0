# Homework 0: Test GitHub Classroom Workflow
We will use this homework assignment to test the Github Classroom workflow that we will use to submit assignments in this course. This homework will not be graded. Use this opportunity to make sure that you have everything setup before working with the homework assignments. Do not hesitate to contact the teaching staff if you are stuck.

## Required Software
- [Git](https://git-scm.com/downloads)\
Mac OSX and Linux systems have git pre-installed. Check by running the command `git --version` in a terminal. On Windows, you will use git bash to run git commands.

## Compilation
- You can use any framework that can compile C programs. However, I would recomend that you do it with online VM [Codespaces](https://github.com/features/codespaces). It gives you free 60 hrs of machine time each month. This will be enough for the programming assignments for this course.
- [Codespaces documentation](https://docs.github.com/en/codespaces/overview).

## Setting up SSH

You will need to use the SSH protocol to securely connect to the assignment repository hosted on GitHub. Follow the listed steps below to setup ssh with GitHub:

- If you already have an account, add the Stonybrook email to your existing GitHub account. See [here](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-user-account/managing-email-preferences/adding-an-email-address-to-your-github-account) for reference. If you created a new GitHub account with your Stonybrook email and SBU Net ID as your username, then skip this step.

- Once you have a GitHub account, you will need to setup SSH public and private keys. These keys will be used by GitHub to authenticate your system. If you already have an existing public/private key pair in your system, you can simply use those keys. How do you know your system has these keys? See [here](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/checking-for-existing-ssh-keys). Skip next step, if the keys exist in your system.

- If your system does not have any public/private key pairs, do not panic. We can easily generate a new key pair. See [here](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) on how to generate new keys.

- The next step is add the public/private key pair in your system to your GitHub account. This is how GitHub knows which keys to use for authenticating your system. See [here](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account) for how to add keys to GitHub.

- The final step is to test the SSH connection. See [here](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/testing-your-ssh-connection) for testing your setup.

### Autograding Example: C
This example project is written in C, and tested with make and bash scripts.

### The assignment
The tests are currently failing because we're printing the wrong string. Correcting the `printf` will fix the tests.

### Setup command
N/A

### Run command
`make test`

### Notes
- `gcc` can be used to compile and link C applications for use with existing test harnesses or C testing frameworks.
