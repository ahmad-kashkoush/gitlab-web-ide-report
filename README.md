![GSoC logo](https://user-images.githubusercontent.com/77677278/130192540-6af44626-154e-4a42-b0e1-ae2537008d81.png)

# GSoC'25 - Final Project Report

The following report summarizes the work done during Google Summer of Code 2025, along with the results, scope for improvements, and future work. This also serves as the final project report with all the contributions.


## Basic Info

- Name: Ahmed Kashkoush
- Email: ahmedkashkoush464@gmail.com
- GitLab Username: ahmad-kashkoush
- LinkedIn: https://www.linkedin.com/in/ahmad-kashkoush/
- Project Title: Add Additional Source Control Operations to the Web IDE
- Project Link: https://gitlab.com/gitlab-org/gitlab-web-ide
- Project Tracker: https://gitlab.com/groups/gitlab-org/-/epics/11142
- Proposal Link: https://docs.google.com/document/d/1x9h_joqBWAJe_Pkb28WbgDxcSdRpwZmHEGjRVkgN2IA/edit?usp=sharing

  
## Background


I've contributed to open source, including Jenkins, stdlib, and the Accord Project, and have been amazed by GitLab and its community.

I've learned a lot from open source, such as networking, effective communication, and working on projects that have real impact. I'm fortunate to have met some great friends and mentors who are always ready to help when needed.
## About the Project 

<div align="center">
    <img src="https://cdn.cookielaw.org/logos/aa14a5c8-79e3-442a-8177-464ad850b19d/e46c1d0d-1f66-481f-bc06-5427671431da/253e6fee-c4c0-4b60-bc35-79cdae5dda32/gitlab-logo-100.png" width="400" alt="MARS logo">
</div>


The GitLab Web IDE enables users to modify files, view diffs, commit, and push changes directly from the browser. This reduces the need to clone repositories for minor edits. However, it lacks key Git commands such as commit amend, force push, stash, and rebase; this forces developers to switch to the command line. This disrupts workflow and introduces several challenges.

My project aims to implement additional source control operations in the Web IDE, enhancing the user experience and expanding its capabilities. These improvements will further reduce the need to clone repositories or switch to alternative platforms to perform common version control tasks.


### Expected Outcome
To add support for advanced Git operations in the GitLab Web IDE source control UI, including:
1. Commit & Force Push
2. Amend Commit & Force Push
3. Create Branch
4. Create Branch from Base...
5. Delete Branch
6. Stage/Unstage Changes


## Goals Achieved

1. [x] Commit & Force Push
2. [x] Amend Commit & Force Push
3. [x] Create Branch
4. [x] Create Branch from Base...
5. [x] Delete Branch
6. Stage/Unstage Changes

## Approach and Workflow

My approach to implementing features is straightforward and consists of the following steps:

1. Clearly identify and understand the issue.
2. Learn what it takes to solve the issue using resources provided by my mentor.
3. Confirm my understanding by discussing the issue with my mentor and the wider community.
4. Implement a smaller part of the solution first.
5. Share updates with my mentor to ensure I’m on the right track.
6. Continue implementing the feature and ask for feedback as needed.

## Merge Requests and Issues

| Merge request                                                                                                           | Status  | Description                                                                                                                                                                                                                                                                                                                                            |
| ----------------------------------------------------------------------------------------------------------------------- | ------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [Feat: Add commit and force push](https://gitlab.com/gitlab-org/gitlab-web-ide/-/merge_requests/497)                    | ✅       | Allow users to force push commits without the need to clone the project locally to get the job done.                                                                                                                                                                                                                                                   |
| [Feat: Add commit amend and force push](https://gitlab.com/gitlab-org/gitlab-web-ide/-/merge_requests/507)              | ✅       | Allows users to amend and force push commits from the browser.<br><br>Use cases:<br>1. If a user typed a wrong commit message and needs to update it.<br>2. If a user wants to add, remove, or modify files in the last commit without cloning the project.                                                                                            |
| [Feat: Update confirmation message](https://gitlab.com/gitlab-org/gitlab-web-ide/-/merge_requests/540)                  | ✅       | Adds a warning to users attempting to force push or amend and force push commits; ensures the user is intentional about this operation.                                                                                                                                                                                                                |
| [Feat: Create branch operations](https://gitlab.com/gitlab-org/gitlab-web-ide/-/merge_requests/534)                     | ✅       | Allows users to create branches from the current branch or a selected base branch.<br><br>Use case:<br>1. When a user wants to create a minor merge request faster.                                                                                                                                                                                            |
| [Doc: Add documentation for additional commit operations](https://gitlab.com/gitlab-org/gitlab/-/merge_requests/196036) | ✅       | Updates the documentation for the commit features to improve understanding for new users.                                                                                                                                                                                                                                                              |
| [Feat: Delete branch](https://gitlab.com/gitlab-org/gitlab-web-ide/-/merge_requests/539)                                | Pending | Allows users to delete branches, given they have the required permissions.                                                                                                                                                                                                                                                                              |
| [Feat: Add support for staging changes](https://gitlab.com/gitlab-org/gitlab-web-ide/-/merge_requests/523)              | Pending | Allows users to stage files before committing, instead of committing all changes.<br><br>This feature is foundational for implementing other features such as commit amend without pushing.<br><br>Implementing its filesystem will also make future features like stashing changes easier to build.              |

## Communication and Work Management
- Asynchronous discussions on GitLab issues were the primary mode of communication.  
- Weekly video calls on Zoom were held to get feedback and discuss deliverables with my mentor.  
- The GitLab Discord community channel was used to resolve doubts, share suggestions, and get feedback from the wider community.  
- Daily updates were posted on the issues to keep my mentor informed.
## What I've Learned

Participating in GSoC '25 has been a major learning experience. I made several mistakes along the way, but each one taught me something valuable and helped me grow both technically and interpersonally. Some of the key lessons include:

1. Communicating effectively in a fully remote environment.  
2. Asking better questions to clarify goals and get what I really need.  
3. Managing my time more wisely while handling multiple priorities.  
4. Navigating and understanding large codebases.  
5. Writing clean, maintainable code and testing it properly.  
6. Learning new tools and technologies quickly when needed.  
7. Realizing that delivering a feature involves much more than just coding; user experience, documentation, and peer reviews are all essential parts of the process.


### Technical Learnings

1. Understanding the importance of feature flags and how they are used in real-world products.  
2. Learning and using the VS Code API to build meaningful features.  
3. Improving how I write and structure tests, and learning when mocking is appropriate and when it is not.  
4. Strengthening my TypeScript skills through real-world challenges.  
5. Deepening my Git knowledge, especially around squashing, rebasing, conflict resolution, and how those features are implemented.  
6. Writing cleaner, more composable TypeScript functions with proper types.  
7. Learning how to implement entirely new features without getting overwhelmed or burnt out.

## Note of Thanks

I would like to thank my mentor and the wider community for their continued support throughout this journey. Special thanks to:

- [Enrique Alcántara](https://gitlab.com/ealcantara)  
- [Nick Veenhof](https://gitlab.com/nick_vh)  
- [Niku Singh](https://gitlab.com/NIKU-SINGH)  
- [Lee Tickett](https://gitlab.com/leetickett-gitlab)  
- [Adebayo Adesanya](https://gitlab.com/adebayo_a)  
- [Marcel van Remmerden](https://gitlab.com/mvanremmerden)


## Future Involvement with GitLab

The mentorship I received and the project I worked on have been invaluable. I plan to continue my journey with GitLab after GSoC.

I would like to:

1. Add support for staging changes in the Web IDE.  
2. Collaborate on redesigning the Web IDE's advanced source control operations.  
3. Help new contributors in the wider community.  
4. If possible, introduce new contributors to the Web IDE and review their merge requests. I believe this will benefit them by contributing to a product with major impact, and benefit GitLab by accelerating the development of the Web IDE.
