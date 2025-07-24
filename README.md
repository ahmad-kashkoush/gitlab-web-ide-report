![GSoC logo](https://user-images.githubusercontent.com/77677278/130192540-6af44626-154e-4a42-b0e1-ae2537008d81.png)

# GSoC'25 - Final Project Report

The following report summarizes the work done during Google Summer of Code 2025 along with the results, scope for improvements and future work. This also serves as the final project report with all the contributions.

## Basic Info

- Name: Ahmed Kashkoush
- Email: ahmedkashkoush464@gmail.com
- Gitlab Username: ahmad-kashkoush
- LinkedIn: https://www.linkedin.com/in/ahmad-kashkoush/
- Project Title: Add additional source control operations to the Web IDE
- Project Link: https://gitlab.com/gitlab-org/gitlab-web-ide
- Project Tracker: https://gitlab.com/groups/gitlab-org/-/epics/11142
- Final Report: (todo: ask mentor)
- Proposal Link: https://docs.google.com/document/d/1x9h_joqBWAJe_Pkb28WbgDxcSdRpwZmHEGjRVkgN2IA/edit?usp=sharing

  
## Background

I've contributed to open-source, including Jenkins, stdlib, The Accord Project, and got amazed by GitLab and its community. 

I've learnt a lot from open source such as networking, how to communicate properly, and working on projects that have great impact. I am fortunate enough to have met some great friends and mentors who are always ready to help me when needed.

## About the Project 

<div align="center">
    <img src="https://cdn.cookielaw.org/logos/aa14a5c8-79e3-442a-8177-464ad850b19d/e46c1d0d-1f66-481f-bc06-5427671431da/253e6fee-c4c0-4b60-bc35-79cdae5dda32/gitlab-logo-100.png" width="400" alt="MARS logo">
</div>

Gitlab WEB IDE enables users to modify files, view diffs, commit, and push changes, Directly from the browser. This reduces the need to clone repositories for minor edits. However, it lacks key Git commands such as commit amend, force push, stash, and rebase, which forces developers to switch to the command line. This disrupts workflow and creates several challenges.

My project aims to implement source control operations in the WEB IDE, ensuring a better user experience and expanding capabilities within the WEB IDE environment. These enhancements will reduce the need to clone repositories or use alternative platforms to perform common version control tasks.

### Expected outcome
To add support for advanced Git operations to Gitlab WEB IDE source control UI such as:
1. Commit & Force Push
2. Amend commit & Force push
3. Create Branch
4. Create Branch from base...
5. Delete Branch
6. Stage/unstage changes

## Goals Achieved:

1. [x] Commit & Force Push
2. [x] Amend commit & Force push
3. [x] Create Branch
4. [x] Create Branch from base...
5. [x] Delete Branch
6. Stage/unstage changes

## Approach and Workflow

My approach for implementing the features is straight forward and consist of the following steps:
1. Identify the issue clearrly and understand it
2. Learn what it takes to solve the issue from resources provided by my mentor
3. Assure my understanding to the issue is correct by discussing it with my mentor and wider community
4. Implement a smaller part of the issue
5. share updates with my mentor to assure I'm on the right path
6. Continue implementing the feature and ask for mentor feedback

## Communication and Work Management
- Async Discusssions over GitLab issues were used as the primary mode of Communication
- Weekly video conferences over Zoom were used to get feedbacks and work on deliverables with the mentor
- The GitLab Discord Community channel was used to resolve any doubts, suggestions and comments whenever there was a need to get help from Wider community
- Daily updates over the Issues were given to the mentor


## Merge Requests and Issues

| Merge request                                                                                                           | Status  |
| ----------------------------------------------------------------------------------------------------------------------- | ------- |
| [Feat: Add commit and force push](https://gitlab.com/gitlab-org/gitlab-web-ide/-/merge_requests/497)                    | ✅       |
| [Feat: Add commit amend and force push](https://gitlab.com/gitlab-org/gitlab-web-ide/-/merge_requests/507)              | ✅       |
| [Feat: Update confimation message](https://gitlab.com/gitlab-org/gitlab-web-ide/-/merge_requests/540)                   | ✅       |
| [Doc: add documentation for additional commit operations](https://gitlab.com/gitlab-org/gitlab/-/merge_requests/196036) | ✅       |
| [Feat: delete branch](https://gitlab.com/gitlab-org/gitlab-web-ide/-/merge_requests/539)                                | Pending |
| [Feat: Create branch operations](https://gitlab.com/gitlab-org/gitlab-web-ide/-/merge_requests/534)                     | Pending |
| [Feat: add support for staging changes](https://gitlab.com/gitlab-org/gitlab-web-ide/-/merge_requests/523)              | Pending |
## What I've learnt

I've learnt a lot of technical and interpersonal skills from participating at GSoC'25, such as:

- How to communicate in a completely remote environment.
- How to ask the right questions that will get you to what you really want
- Time management
- Understanding large codebase
- Writing clean code and how to test it
- How to learn a tool or technology very fast



## Future Involvements with the GitLab

The Mentorship I got and the project I'm working on have never been greater. I'm planning to continue my journey with Gitlab after GSoC. 

I would like to:
1. Add support for staging changes in Web IDE. 
2. Collaborate in redesigning the web IDE advanced source control operations
3. Help new contributors in the wider community


