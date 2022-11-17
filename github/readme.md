## GitHub

GitHub will work alongside the `git` command line program to allow you to back up your code and collaborate with other developers. To get started, go to [github.com](https://github.com). Then, click the Sign Up button.

![GitHub landing page.](./assets/landing-page.png)

After clicking Sign Up, you will be prompted to enter your email address. This one time, you should use your personal email address.

![GitHub sign-up screen.](./assets/github-wizard.png)

Follow the additional instructions, including picking out a username. For your username, pick something professional like your name.

You will then be sent an email with a confirmation code. Fill in the confirmation code to complete the process.

![confirmation code screen.](./assets/confirmation.png)

Enter the code. You will then be brought to another screen that will offer to help you get started with GitHub.

![getting started page.](./assets/getting-started.png)

At this point, you have a GitHub account. You do not need to click any of these buttons and can instead click "Skip this for now."

### Customizing Git with GitHub credentials

Now that you have GitHub, you can provide some customizations to Git. Run the following command to allow Git to know your username. Replace `USERNAME` with the username you defined on GitHub.

```
git config --global user.name "USERNAME"
```

Now run the following command, replacing `EMAIL` with the email you used to sign up for GitHub.

```
git config --global user.email "EMAIL"
```

### Creating a Personal Access Token (PAT)

To connect Git and GitHub fully, you will need to log in to GitHub through the `git` program. This requires the creation of a Personal Access Token, also called a PAT. The following link will provide resources on how to set up your own PAT.

- [GitHub: Creating a PAT](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)

In the rare case you are switching from using a password to using a PAT, you may find the following guide useful:

- [Changing from Password to PAT on GitHub](../pat-set-up/readme.md)
