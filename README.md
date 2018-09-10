# COLLAB_WORKFLOW

How to collaborate on a project

## Overview

Every project attempts to achieve two simulatenous goals:

 1. Allow and receive contributions from many
 2. Make sure the project's integrity is preserved

 The following describes a process for working with code or ASCII documents using github as a repository. 

## Basic steps

 1. Each developer forks from `https://githulb.com/pletzer/collab_workflow`. Click on the fork button. 
 2. Each developer creates a branch within their own repository. A branch represents an idea, concept, bug fix and should be named apropriately. For instance `new_population_assessment`. The developer then commits locally to their branch `git commit -a`, then pushes to the remote branch `git push origin new_population_assessment`. 
 3. When the new code is ready to be merged to the master branch, the developer:
    * merges the master branch to the current branch (to pick up any changes since the branch split from master), `git https://https://githulb.com/pletzer/collab_workflow`
    * commits and pushes to their own remote repository `git push origin new_population_assessment`
    * creates a pull-request on the web site. 

## Example
