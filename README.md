# Git Version Control Learning Path

This comprehensive roadmap provides a structured approach to mastering Git version control. The curriculum is designed sequentially, with each module building upon previous knowledge to ensure a solid foundation in version control practices.

```mermaid
flowchart TD
    A[Start Git Journey] --> B[Fundamentals<br>Weeks 1-2]
    B --> C[Branching & Merging<br>Weeks 3-4]
    C --> D[Collaboration<br>Weeks 5-6]
    D --> E[Advanced Git<br>Weeks 7-8]
    E --> F[Workflows & CI/CD<br>Week 9+]
    
    B --> B1[Concepts & Setup]
    B1 --> B2[Basic Commands]
    B2 --> B3[Staging & Committing]
    B3 --> B4[History & Logs]
    
    C --> C1[Branch Creation]
    C1 --> C2[Merging Strategies]
    C2 --> C3[Rebase vs Merge]
    C3 --> C4[Conflict Resolution]
    
    D --> D1[Remote Repositories]
    D1 --> D2[Push/Pull/Fetch]
    D2 --> D3[Collaborative Work]
    D3 --> D4[Pull Requests]
    
    E --> E1[Undoing Changes]
    E1 --> E2[Stashing]
    E2 --> E3[Hooks]
    E3 --> E4[Advanced Tools]
    
    F --> F1[GitFlow]
    F1 --> F2[GitHub Actions]
    F2 --> F3[CI/CD Integration]
```

---

## Phase 1: Git Fundamentals & Basic Concepts (Weeks 1-2)

*   [**Module 1: Introduction to Version Control**](https://github.com/ahmadrizal1st/git-intro/#readme)
    *   What is Version Control and why it's essential
    *   Centralized vs Distributed Version Control Systems
    *   Git history and design philosophy
    *   Common Git workflows and use cases
    *   Installing Git on different operating systems

*   [**Module 2: Git Configuration & Setup**](https://github.com/ahmadrizal1st/git-setup/#readme)
    *   First-time Git setup: `git config`
    *   User configuration: name, email, and editor settings
    *   Global vs Local configuration levels
    *   SSH key generation and authentication setup
    *   Basic Git help and command documentation

*   [**Module 3: Creating Repositories & Basic Commands**](https://github.com/ahmadrizal1st/git-repositories/#readme)
    *   Initializing a new repository: `git init`
    *   Cloning existing repositories: `git clone`
    *   Repository structure: working directory, staging area, repository
    *   Git file lifecycle: untracked, modified, staged, committed
    *   Checking repository status: `git status`

*   [**Module 4: Staging and Committing Changes**](https://github.com/ahmadrizal1st/git-committing/#readme)
    *   Staging files: `git add` (specific files, directories, all changes)
    *   Committing changes: `git commit` with meaningful messages
    *   Commit best practices: atomic commits and message conventions
    *   Skipping the staging area: `git commit -a`
    *   Viewing commit history: `git log` with various options

---

## Phase 2: Branching & Merging Strategies (Weeks 3-4)

*   [**Module 5: Branching Fundamentals**](https://github.com/ahmadrizal1st/git-branching/#readme)
    *   What are branches and why use them?
    *   Creating and switching branches: `git branch`, `git checkout`
    *   Modern branch switching: `git switch` and `git restore`
    *   Listing and deleting branches
    *   Understanding HEAD pointer and branch references

*   [**Module 6: Basic Merging**](https://github.com/ahmadrizal1st/git-merging/#readme)
    *   Fast-forward merges vs three-way merges
    *   Performing merges: `git merge`
    *   Merge commit messages and conflict indicators
    *   Best practices for merging branches
    *   Checking differences between branches: `git diff`

*   [**Module 7: Rebasing**](https://github.com/ahmadrizal1st/git-rebasing/#readme)
    *   Understanding rebase vs merge differences
    *   Interactive rebasing: `git rebase -i`
    *   Rebasing workflow and when to use it
    *   Squashing commits with rebase
    *   Dangers and benefits of rebasing

*   [**Module 8: Conflict Resolution**](https://github.com/ahmadrizal1st/git-conflicts/#readme)
    *   Understanding merge conflicts and their causes
    *   Conflict markers and how to read them
    *   Resolving conflicts manually
    *   Using merge tools for conflict resolution
    *   Aborting merges and rebases when needed

---

## Phase 3: Remote Repositories & Collaboration (Weeks 5-6)

*   [**Module 9: Working with Remote Repositories**](https://github.com/ahmadrizal1st/git-remote/#readme)
    *   Adding remote repositories: `git remote add`
    *   Viewing and managing remotes: `git remote -v`
    *   Pushing to remotes: `git push`
    *   Fetching from remotes: `git fetch`
    *   Pulling changes: `git pull` and its components

*   [**Module 10: Collaborative Workflows**](https://github.com/ahmadrizal1st/git-collaboration/#readme)
    *   Forking workflow vs feature branch workflow
    *   Creating and managing pull requests/merge requests
    *   Code review practices with Git
    *   Managing multiple remotes (origin, upstream)
    *   Syncing forked repositories

*   [**Module 11: Tags and Releases**](https://github.com/ahmadrizal1st/git-tags/#readme)
    *   Creating lightweight tags: `git tag`
    *   Creating annotated tags: `git tag -a`
    *   Pushing tags to remote: `git push --tags`
    *   Using tags for versioning and releases
    *   Checking out specific tags

*   [**Module 12: GitHub/GitLab/Bitbucket Platforms**](https://github.com/ahmadrizal1st/git-platforms/#readme)
    *   Creating repositories on hosting platforms
    *   README files, .gitignore, and license files
    *   Using issues and project boards
    *   Wiki and documentation features
    *   Social coding aspects: starring, watching, forking

---

## Phase 4: Advanced Git Techniques (Weeks 7-8)

*   [**Module 13: Undoing Changes**](https://github.com/ahmadrizal1st/git-undo/#readme)
    *   Unstaging files: `git reset`, `git restore --staged`
    *   Discarding working directory changes: `git checkout --`, `git restore`
    *   Amending commits: `git commit --amend`
    *   Reverting commits: `git revert` (safe method)
    *   Resetting commits: `git reset` (soft, mixed, hard)

*   [**Module 14: Stashing and Cleaning**](https://github.com/ahmadrizal1st/git-stashing/#readme)
    *   Stashing changes: `git stash` and `git stash push`
    *   Applying and popping stashes
    *   Managing multiple stashes
    *   Stashing untracked files and using options
    *   Cleaning working directory: `git clean`

*   [**Module 15: Git Hooks**](https://github.com/ahmadrizal1st/git-hooks/#readme)
    *   Understanding Git hooks and their types
    *   Client-side hooks: pre-commit, prepare-commit-msg
    *   Server-side hooks: pre-receive, update
    *   Creating custom hooks
    *   Hook management and best practices

*   [**Module 16: Advanced Tools & Techniques**](https://github.com/ahmadrizal1st/git-advanced/#readme)
    *   Interactive staging: `git add -p`
    *   Bisecting to find bugs: `git bisect`
    *   Worktree for multiple working directories
    *   Submodules for including other repositories
    *   Cherry-picking specific commits

---

## Phase 5: Git Workflows & Professional Practices (Week 9+)

*   [**Module 17: Git Workflow Strategies**](https://github.com/ahmadrizal1st/git-workflows/#readme)
    *   **GitFlow Workflow**: feature, release, hotfix branches
    *   **Trunk-Based Development**: short-lived feature branches
    *   **Forking Workflow**: open source collaboration model
    *   **Feature Branch Workflow**: team collaboration standard
    *   Choosing the right workflow for your project

*   [**Module 18: .gitignore Patterns**](https://github.com/ahmadrizal1st/git-ignore/#readme)
    *   Purpose of .gitignore files
    *   Global vs local .gitignore
    *   Pattern matching syntax and examples
    *   Common patterns for different languages/frameworks
    *   Ignoring already tracked files

*   [**Module 19: CI/CD Integration**](https://github.com/ahmadrizal1st/git-ci-cd/#readme)
    *   GitHub Actions workflows
    *   GitLab CI/CD pipelines
    *   Automated testing with Git hooks
    *   Deployment strategies with Git
    *   Quality gates and automated checks

*   [**Module 20: Enterprise Git Practices**](https://github.com/ahmadrizal1st/git-enterprise/#readme)
    *   Branch protection rules
    *   Code ownership and review requirements
    *   Signed commits and verification
    *   Audit trails and compliance
    *   Backup strategies and disaster recovery
