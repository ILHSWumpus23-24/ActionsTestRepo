# Test Repository for Github Actions

## How to stop pushing into the Main or Master branch

For each repository, we go to the settings tab on Github and click on the "Branch" item on the left side of the page and create a "Branch Protection Rule" as shown below ![photo of Github as described](./assets/Branch-protection-rule.png)

The "Require a pull request before merging" seems like the obvious pace to start.

Turns out we need to "Restrict who can push to matching branches." ![photo of Github](./assets/Restrict-pushes.png)

This setting still allows administrators to do pushes directly to the main branch, though.

More details about the options chosen on the page above is available at this [manaul page](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/about-protected-branches).
