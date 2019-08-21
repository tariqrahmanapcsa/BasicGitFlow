# GitLabFlow
Team Names:  Soumya Kakarlapudi, Manogna Namburu, Tariq Rahman, Jonathan Wang
GitLab Workflow

Description of Basic Git workflow: 

In the Basic Git workflow, there is a master with number of developers that each have a cloned repository of the original. Each person initializes their own local repository which would contain their individual working directory. Changes are made to their local copy of master which are eventually staged and commited. The branches themselves would include the history of the project whereas the master branch stores the beginning of it. 

Description of GitLab workflow:
The GitLab workflow uses a master branch and a series of developer branches. The developer branches are used for fixing errors and developing new features before the developers push the modifications back as new branches to the repository. Any additional features or modifications will begin at those newly modified developer branches. The new branches essentially become the latest version of the project. This type of workflow is useful for large-scale projects that need to be constantly deployed at all times. The project would update to the latest and most up-to-date branch which would act like the master.   

Key Differences from basic workflow, and key use cases
- GitFlow is the simple and safer alternative because GitLab offers many complications that could cause errors
- Uses production, environment, and release branches in addition to the master and feature/merge requests used in GitFlow.
- Instead of constantly merging new modifications with the master branch, newly edited local branches of the master are pushed into the repository as the new updated version in GitLab. 

Link to your Git example repository: https://github.com/tariqrahmanapcsa/GitLabFlow 

Documentation of git commands used, and annotated sample sequence of commands used in creating your repository

1. git init
2. git clone https://github.com/tariqrahmanapcsa/GitLabFlow.git 
3. git checkout -b “branch-name”
4. git diff
5. git add
6. git status .
7. git commit -m “message”
8. git push --set-upstream origin <branch-name>
