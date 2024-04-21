# Harsh-Atulkar-Learning-Git
Repository for Git certification assignment

### Introduction
The aim of this report is to provide clear description of the methods for achieving the tasks given in this assignment. It provides step by step screenshots of tasks being completed.

## 1. Setup:
   - Install Git on your system.
   - You can download Git from the official website: https://git-scm.com/
     ![Screenshot from 2024-04-21 09-10-30](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/9b6dfd58-c1e7-4958-b082-8e1adbb6f8b5)

   - Create a GitHub account.
     Go to https://github.com/ and sign up for an account if you haven't already.
     ![Screenshot from 2024-04-21 09-11-55](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/f7cd688c-92a2-4fc7-bd9d-8debdd26c0de)

   - Install Visual Studio Code (VSC) and GitHub Desktop.
![Screenshot from 2024-04-21 09-11-20](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/5da557ed-d356-4627-9a38-6d246f662fa9)
![Screenshot from 2024-04-21 09-09-33](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/9f51adb9-150a-4ebd-ba9f-141c62ed8d23)


## 2. Repository Creation:
   - Create a new repository on GitHub.
    Log in to your GitHub account.
    Click on the "+" sign in the top right corner and select "New repository".
    Name your repository 
    Optionally, you can add a description for your repository.
    Choose whether the repository should be public or private.
    Click on "Create repository" to finish.
     ![Screenshot from 2024-04-21 09-21-34](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/87dceb1e-e97a-4b29-aa19-eee947b9a94e)
     ![Screenshot from 2024-04-21 09-21-54](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/2395231c-e650-4ced-ae93-a0ed40a3f273)


   - Clone the repository to your local machine.
     Write "git clone <repo url>" to clone the remote repository
     ![Screenshot from 2024-04-21 09-57-34](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/c8b21771-7a74-4dcb-a0ca-338f880fbdca)


   - Set up Git configurations (username, email, etc.).
     ![Screenshot from 2024-04-21 09-59-52](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/d0046a38-13fd-4886-879e-d1adc19626fd)


## 3. Basic Commands:
   - Create a new branch named "feature-branch" from the main/master branch.
     ![Screenshot from 2024-04-21 19-25-16](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/4f65b7c6-7b9a-4f8c-96dc-e5f295765842)


   - Make changes to a file (e.g., add, modify, delete).
   - Add your changes to the staging area.
   - Commit your changes with a meaningful commit message.
     ![Screenshot from 2024-04-21 19-28-05](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/f2f539e1-a581-4736-81da-596baa8f91b1)

   - Push your changes to the remote repository.
     ![Screenshot from 2024-04-21 19-43-35](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/caaca6b9-7f61-4f76-95d0-be9abfea2bbd)
     ![Screenshot from 2024-04-21 19-43-48](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/587722f2-6a4e-4915-9f26-5e634a82e2e5)



4. Working with Others:
   - Create a new branch named "collaborator-branch" from the primary/master branch.
     ![Screenshot from 2024-04-21 19-45-14](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/529b5346-a375-46fc-a6af-19c804c88b17)

   - Make conflicting changes to the same file in both branches.
     ![Screenshot from 2024-04-21 19-48-03](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/4d3552e7-89db-4ab0-bf2e-b6de6f1b2831)

   - Merge the "feature-branch" into the main/master branch.
     ![Screenshot from 2024-04-21 19-52-27](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/5895bb36-da34-4094-a6f8-c44914647f7f)

   - Resolve any merge conflicts that arise.
     ![Screenshot from 2024-04-21 19-51-57](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/e63fc236-45d3-445c-b0f2-5249426d1198)
     ![Screenshot from 2024-04-21 19-54-57](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/323bc89b-7ed0-4672-a903-5cd7c2ba75f4)


## 5. Undoing Changes:
   - Use Git checkout to switch to a previous commit.
     First, find the commit you want to revert to by using the git log command to view the commit history.
     Copy the commit hash or identifier of the desired commit.
     Use the following command to switch to that commit:

      git checkout <commit-hash>
   ![Screenshot from 2024-04-21 19-57-59](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/3796db85-52d3-428e-837b-c6d950b9ac04)


 - Use Git reset to undo the last commit.
     ![Screenshot from 2024-04-21 20-09-01](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/11b68f5b-95d8-4714-954a-a54e74e98cbc)
     ![Screenshot from 2024-04-21 20-09-05](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/07dbc866-de9d-47e8-b362-6d575b435a8d)

   
  - Use Git revert to undo a specific commit.
      To undo the last commit and keep the changes in the working directory, you can use the soft reset option:

      git reset --soft HEAD~1

      This command moves the HEAD pointer to the previous commit, effectively undoing the last commit but keeping the changes staged.
     ![Screenshot from 2024-04-21 20-11-20](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/47920621-75b0-4a48-90dc-6d3e8587ba53)
     ![Screenshot from 2024-04-21 20-13-47](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/0cff8508-540f-4128-8bdf-98dc2cd61f07)


## 6. GitHub Practice:
   - Create a pull request from "collaborator-branch" to main/master.
      ![Screenshot from 2024-04-21 20-17-02](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/f4a6a2be-ce72-47f0-8bfd-281abf3d52bb)
      ![Screenshot from 2024-04-21 20-19-08](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/318c1ccb-d6e0-42e3-a450-c2cc2b916bea)
      ![Screenshot from 2024-04-21 20-19-23](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/6349c40a-9299-4de9-9876-67cbdb3e015d)


   - Fork a repository from another user's account. (Fork this repo - https://github.com/Tanvi-Ambre/Movie_Search)
      ![Screenshot from 2024-04-21 20-28-08](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/b84baad4-81f3-415e-8e98-83cf7f97a492)
      

   - Create a new branch in the forked repository.
        ![Screenshot from 2024-04-21 20-33-16](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/05fd46c7-4ab9-488f-9394-465219a79344)
        

   - Make changes and create a pull request to the original repository.
        ![Screenshot from 2024-04-21 20-35-25](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/b224798b-3a23-4b7c-843d-2f321b3090c8)
        ![Screenshot from 2024-04-21 20-36-15](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/2a01b1eb-d7a2-479e-a7c4-7602d6eb3559)
        ![Screenshot from 2024-04-21 20-37-13](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/5a2222e2-0b67-4df8-b98d-e969ba02eb6e)


## 7. Advanced Tools and Hosting:
   - Use the Git Lens extension in Visual Studio Code to visualize Git history.
      Open Visual Studio Code and navigate to your project directory.
      Install the Git Lens extension from the Visual Studio Code marketplace if you haven't already.
      Once installed, you can use Git Lens to visualize Git history, explore commits, view file changes over time, and more directly within Visual Studio Code.
      ![Screenshot from 2024-04-21 20-44-35](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/1d04541a-219f-4a5d-8e19-3cf792f459a1)

   - Deploy a static website using GitHub Pages.
     ![Screenshot from 2024-04-21 22-50-47](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/ae099dd6-0eb2-4677-b63f-157689c3770c)

   - Paste a screenshot of the hosted page, make sure the url is visible on the published page.
     ![Screenshot from 2024-04-21 22-50-10](https://github.com/thedead101/Harsh-Atulkar-Learning-Git/assets/96925476/c51e739d-a343-4e10-a124-191f87154007)

