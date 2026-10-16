## Starting Structure
the initial structure has 6 branches: main, dev, feature1, feature2, feature3, and hotfix.
Feature1, Dev, Feature3 and hotfix are descendants of main. Feature2 is a descedant of dev. 

## Starting Branch Changes
main is the initial game and code dump. Feature1 added using a negative number to exit 
the game and an option to play again. Feature2 aded the max number of attempts and a game 
over condition. Feature3 added a hint if you were very close to the correct number. Dev 
added an encouraging message for players. Hotfix fixed a bug in utils to include the max 
value within the range.

## Learning
### Differences between Merge, Rebase, Squash, Cherry-Pick
- Merge pulls all code from a target branch into your current (HEAD) branch. Conflicts may 
need to be resolved.
- Rebase keeps history linear by adding commits on top of the latest state of a another 
branch. It reapplies your current commits to the top of a target branch. Good for when 
main/master gets edited while working on a feature branch.
- Squash takes mutiple commits and pushes them into one for easier logging and readability. 
Can take many commits anc lean them up into a better structure.
Cheery-pick pulls code from a specific commit into the current branch/HEAD.

### Observed in git history
Feature commits show that they worked on different features that were being added to the
program. Feature 1 has commits that focus on player experience improvement to the game.
Feature 2 had more of a focus on game winning conditions and game over logic. Feature 3 
brought in game hints for the player. 


### Use in real projects
I can use what i have learned from this assignment in my personal coding projects to better 
manage my projects structure and versions. Branching allows me to separate features and 
functionality without hurting the integrity of the working project. I can use merging to pull 
the new tested features into my working project. Rebasing allows me to clean up and keep well 
organized commit history. Cherry-picking would allwo me to pull specific commits without 
having to pull entire branches.