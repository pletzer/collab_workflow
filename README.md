# COLLAB_WORKFLOW

How to collaborate on a project

## Overview

Every project attempts to achieve two simulatenous goals:

 1. Allow and receive contributions from many
 2. Make sure the project's integrity is preserved

 The following describes a process for working with code or ASCII documents using github as a repository. 

## Basic steps

 1. Each developer forks from `https://githulb.com/pletzer/collab_workflow`. Click on the fork button [DESCRIBE]. 
 2. Each developer creates a branch within their own repository. A branch represents an idea, concept, bug fix and should be named appropriately. In the following we call our new development branch `new_population_assessment`. The developer  
    * commits locally to their branch `git commit -a`
    * then pushes to the remote branch, `git push origin new_population_assessment`. 
 3. When the new code is ready to be merged to the master branch, the developer:
    * first merges the master branch to the current branch (to pick up any changes since the branch split from master)
      * `git https://https://githulb.com/pletzer/collab_workflow`
    * commits and pushes to their own remote repository
      * `git push origin new_population_assessment`
    * creates a pull-request on the web site, justifying in the text box by the change is important. The gate-keepers will assess the change to the repository. There can be back and forth discussion, all captured in the text boxes. Finally the gate-keeper agrees with the change and the `new_population_assessment` code is merged to the master branch. At that point the `new_population_assessment` can be deleted.

