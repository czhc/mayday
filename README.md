# mayday
A repository to demonstrate recovery from hard resets and force push


## Quiz (survival guide) 

There’s a project called `coin-inu`. Alice and Bob are devs in the project. The `main` branch is currently at commit `001`.

The following happened: 
* Alice checks out from `main`  into `feature/alice`, makes the changes, submits a PR and gets it merged. It took her 2 weeks to finish the feature. `main` is now updated to `00A`
* Bob pulls from `main` at commit `00A` . Makes some simple changes with commit `00B`  and pushes it directly to `main`
* Bob realizes his changes are breaking prod. He looks into the git log, resets main back to `001` and uses `git push --force`. Bob feels good and goes home.
* Alice’s commits in `00A`  is lost. 

Help Alice recover her work, without making her redo the work.

