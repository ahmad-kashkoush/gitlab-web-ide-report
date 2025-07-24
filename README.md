![GSoC logo](https://user-images.githubusercontent.com/77677278/130192540-6af44626-154e-4a42-b0e1-ae2537008d81.png)

# GSoC'25 - Final Project Report

The following report summarizes the work done during Google Summer of Code 2025 along with the results, scope for improvements and future work. This also serves as the final project report with all the contributions.


## Basic Info

- Name: Ahmed Kashkoush
- Email: ahmedkashkoush464@gmail.com
- GitLab Username: ahmad-kashkoush
- LinkedIn: https://www.linkedin.com/in/ahmad-kashkoush/
- Project Title: Add Additional Source Control Operations to the Web IDE
- Project Link: https://gitlab.com/gitlab-org/gitlab-web-ide
- Project Tracker: https://gitlab.com/groups/gitlab-org/-/epics/11142
- Final Report: (todo: ask mentor)
- Proposal Link: https://docs.google.com/document/d/1x9h_joqBWAJe_Pkb28WbgDxcSdRpwZmHEGjRVkgN2IA/edit?usp=sharing

  
## Background


I've contributed to open source, including Jenkins, stdlib, and The Accord Project, and have been amazed by GitLab and its community.

I've learned a lot from open source, such as networking, how to communicate effectively, and working on projects that have a great impact. I am fortunate to have met some great friends and mentors who are always ready to help when needed.

## About the Project 

<div align="center">
    <img src="https://cdn.cookielaw.org/logos/aa14a5c8-79e3-442a-8177-464ad850b19d/e46c1d0d-1f66-481f-bc06-5427671431da/253e6fee-c4c0-4b60-bc35-79cdae5dda32/gitlab-logo-100.png" width="400" alt="MARS logo">
</div>


The GitLab Web IDE enables users to modify files, view diffs, commit, and push changes directly from the browser. This reduces the need to clone repositories for minor edits. However, it lacks key Git commands such as commit amend, force push, stash, and rebase, which forces developers to switch to the command line. This disrupts workflow and creates several challenges.

My project aims to implement additional source control operations in the Web IDE, ensuring a better user experience and expanding capabilities within the Web IDE environment. These enhancements will reduce the need to clone repositories or use alternative platforms to perform common version control tasks.


### Expected Outcome
To add support for advanced Git operations to the GitLab Web IDE source control UI, such as:
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


My approach for implementing the features is straightforward and consists of the following steps:
1. Identify the issue clearly and understand it
2. Learn what it takes to solve the issue from resources provided by my mentor
3. Ensure my understanding of the issue is correct by discussing it with my mentor and the wider community
4. Implement a smaller part of the issue
5. Share updates with my mentor to ensure I'm on the right path
6. Continue implementing the feature and ask for mentor feedback


## Communication and Work Management
- Asynchronous discussions over GitLab issues were used as the primary mode of communication
- Weekly video conferences over Zoom were used to get feedback and work on deliverables with my mentor
- The GitLab Discord Community channel was used to resolve any doubts, suggestions, and comments whenever there was a need to get help from the wider community
- Daily updates over the issues were given to my mentor


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
## What I've Learned

I've learned a lot of technical and interpersonal skills from participating in GSoC'25, such as:

- How to communicate in a completely remote environment
- How to ask the right questions to get to what you really want
- Time management
- Understanding large codebases
- Writing clean code and how to test it
- How to learn a tool or technology very quickly



## Note of Thanks

I would like to thank my mentor and the wider community for their support. Special thanks to:
- [Enrique Alcántara](https://gitlab.com/ealcantara)
- [Nick Veenhof](https://gitlab.com/nick_vh)
- [Niku Singh](https://gitlab.com/NIKU-SINGH)
- [Lee Tickett](https://gitlab.com/leetickett-gitlab)
- [Adebayo Adesanya](https://gitlab.com/adebayo_a)
- [Marcel van Remmerden](https://gitlab.com/mvanremmerden)



## Future Involvement with GitLab

The mentorship I received and the project I'm working on have been invaluable. I'm planning to continue my journey with GitLab after GSoC.

I would like to:
1. Add support for staging changes in the Web IDE
2. Collaborate in redesigning the Web IDE's advanced source control operations
3. Help new contributors in the wider community


