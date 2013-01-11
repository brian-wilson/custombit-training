# Git Commit Messages


## The Principle

Write git commit messages to maximize the usefulness of git commands like log and blame.

This makes it much easier to collaborate on, maintain and extend an app.

### Do it for posterity!

Your git commits will last as long as the repo.

### Possible use cases

Review new code.

Undo a feature.

Why did we do it like this?

How long has this been broken?

Changelog for updating live.


## A Few Guidelines

### Describe what the commit does

Messages like "Fixed bug" or "Changes" are useless.

### One sentence that's not too long

Answer the question "What does this code do?"

Include a verb.

The git plugin guy [suggests][1] about 50 characters. Linux kernel [guidelines][2] say "no more than 70-75 characters". Github chops it up after 70.

> It is challenging to be both succinct and descriptive, but that is what a well-written summary should do.

### Add more detail in a paragraph

This is optional, don't just restate the summary line.

The details can explain what bug needed fixing, why you did something that way, known side effects, relevant links, jokes, [threats][3]. etc.

### Split or merge the commit if necessary

Git rebase interactive. Git commit amend.

One logical chunk.

### Include the issue number

Links to more info.

Easier to find all commits related to a certain feature/bugfix.

For Redmine that's "refs #123", for github just "#123".

### Present tense

"Fixes bug" not "fixed bug".

Answer the question "What does this code do?". Not "What task does this resolve?" or "What bug does this fix?" or "What did I do?"

### Capitalize and punctuate

Because I'm OCD like that.

[1]: http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html
[2]: http://git.kernel.org/?p=linux/kernel/git/torvalds/linux.git;a=blob;f=Documentation/SubmittingPatches;h=c379a2a6949f1c1cac04fb6f185c633512f37061;hb=HEAD#l521
[3]: https://github.com/rails/rails/commit/e80546cdec56a9c3fcaf6217cba08a02d789d2bc
