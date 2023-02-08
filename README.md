# Git and Github Setup Guide

## Prerequisites

* You need to have Git installed on your computer. If not, please follow the installation guide for your operating system.

## Configuring Basic Info

Before creating a repository, it is important to configure your name and email on your local machine, as they will be part of your commits.

1. Open Git terminal/command prompt
2. Type the following commands:

```bash
git config --global user.name "Your name"
git config --global user.email "your_email@example.com"
```
 ## Creating a Repository on Github
1. Go to Github.com and sign in to your account.
2. Click on the `+` icon on the top right corner and select `New repository`.
3. Enter the repository name as `zero_day`.
4. Choose `Public` for the repository visibility.
5. Deselect the options for `README`, `.gitignore`, and `License`.
6. Click on the `Create repository` button.

## Setting Up the Local Repository
1. Open Git terminal/command prompt.
2. Navigate to your home directory by typing the following command:

```bash
cd ~
```
3. Create a new directory named `zero_day` by typing the following command:

```bash
mkdir zero_day

```
4. Navigate to the newly created directory by typing the following command:
```bash
cd zero_day

```
5. Initialize Git in the directory by typing the following command:
```csharp
git init

```
6. Add the remote origin of the repository created on Github by typing the following command:
```bash
git remote add origin https://github.com/<your_username>/zero_day.git

```

## Creating a README file
1. Open Git terminal/command prompt and navigate to the `zero_day` directory.
2. Create a file named `README.md` by typing the following command:
```bash
emacs README.md

```
(Note: You can use any command-line text editor such as nano or vim instead of emacs)

3. Write a small Markdown text to present this project and save the file.
## Pushing Changes to Remote Repository
1. Add the README file to Git by typing the following command:
```csharp
git add README.md

```
2. Commit the changes with the message "My first commit" by typing the following command:
```bash
git commit -m "My first commit"

```
3. Push the changes to the remote repository by typing the following command:
```perl
git push origin master

```
(Note: You will be prompted to enter your Github username and password)
