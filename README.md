# Rebase Brown Bag

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.1.0.

## Start

Start by checking out the `feature` branch of this project, and feel free to make any modifications to this project.

## Rebase

Since the feature branch has been created, new changes have been merged to the `master` branch. To pull these changes into your branch, execute `git rebase master`.

## Resolve Conflicts

Utilities like IntelliJ or GitKraken often have built in GUI conflict resolvers, but you can also resolve conflicts directly from the source code file.

If resolving with IntelliJ, open the "Version Control" panel and right click on the changes to resolve conflicts.

If resolving directly in the source code file, you'll see the conflicts broken up into two chunks of code. The first chunk is code from the branch you are rebasing onto (in this case `master`) and the second chunk is the feature branch you are rebasing from (in this case `feature`). To resolve the conflict, remove the extra characters and manually make the necessary edits.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.
