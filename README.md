# gitSandbox
Sandbox to play with git and SourceTree


## Prerequisite

You may need a Markdown viewer/reader extension for your web broswer to properly view this `README.md`.

* Chrome: [Markdown Reader](https://chrome.google.com/webstore/detail/markdown-reader/gpoigdifkoadgajcincpilkjmejcaanc?hl=en)
* Firefox: [Markdown Viewer](https://addons.mozilla.org/en-us/firefox/addon/markdown-viewer/)


## Task 1: Get git GUI

1. Download and install [SourceTree](http://www.sourcetreeapp.com/).
2. Click the *Tools|Options* menu choice.
3. In the *General* tab,
  * Change the *Default user information* to your name and email address.
  * Change the *Project folder* in the *Misc* section to `H:\`.
4. Click *OK*.

Now you are ready to clone a repository.


## Task 2: Clone an existing repository

1. Click the *Clone/New* icon on the toolbar (*Ctrl+N*).
2. Click the *Clone Repository* tab.
3. In the *Source Path/URL* text box, enter  
    [`X:/OHSU Shared/Restricted/OCHSER/Resources/Code_Sharing/gitSandbox.git`](file:///X:/OHSU%20Shared/Restricted/OCHSER/Resources/Code_Sharing/gitSandbox.git/).
4. Confirm that the *Repository Type* says `This is a Git repository`.
5. Confirm that the *Destination Path* is `H:\gitSandbox`. This will create a folder named `gitSandbox` in the *Project folder* you assigned earlier.
5. Click the *Clone* button.
6. Navigate to the [`H:\gitSandbox`](file:H:/gitSandbox/) folder (click the link) and confirm that you have the files listed [here](https://github.com/benjamin-chan/gitSandbox/tree/StartHere) (you may not see `.gitignore`; if you don't, don't worry, it's there but hidden).

Now you are ready to create and stage a new file.


## Task 3: Stage a new file

1. Using a text editor (e.g., Notepad, [Notepad++](http://notepad-plus-plus.org/), [Sublime](http://www.sublimetext.com/), [Atom](https://atom.io/)), create a text file.
    * Fill the text file with a bunch of text.
    * Or copy-paste the contents of another text file into this empty file.
    * If don't feel creative, use a random text generator, like [Lorem Ipsum](http://www.lipsum.com/).
2. Save the file as `H:\gitSandbox\<your-first-name>.txt`.
3. In SourceTree, switch to File Status view (click the *View|File Status View* menu choice, or press *Ctrl+1*)
4. In the lower middle pane labeled *Unstaged files*, check the box next to your `<your-first-name>.txt` file.
    * Notice that the `<your-first-name>.txt` file moves from the *Unstaged files* pane (lower middle pane) to the *Staged files* pane (upper middle pane)

Now you are ready to commit this addition.


## Task 4: Commit an addition

1. In SourceTree, switch to File Status view (click the *View|File Status View* menu choice, or press *Ctrl+1*)
2. At the bottom, type in a *Commit message* describing the new file.
3. Click the *Commit* button.

Now you are ready to make and stage edits to an existing file.

### Suggested guidelines for commit messages

Commit messages should

* Use a **verb-object** structure
    * Good: *Add LaTeX file for my poster*
    * Bad: *The LaTeX file for my poster was added*
* Use verbs in the **present tense**
    * Good: *Add*
    * Bad: *Added*
* Answer **what** and **why**
    * No need to answer **how**, **when**, or **who**; these are automagically tracked by git
    * Good: *Add LaTeX file for my poster per Ben's request*
    * Bad: *I added lines 22-24 to the LaTeX file for my poster on 2015-04-15*
* Use easily **searchable and specific keywords**
    * Good: *Increase the number of ICD-9 codes used from 4 to 13*
    * Bad: *Make changes to the files*


## Task 5: Stage edits

1. Edit the text file `H:\gitSandbox\<your-first-name>.txt`.
    * Add a line with the sentence `I made an edit here.`.
    * Delete a line of text in your file.
2. Save the file.
3. In SourceTree, switch to File Status view (click the *View|File Status View* menu choice, or press *Ctrl+1*)
4. In the lower middle pane labeled *Unstaged files*, click the `<your-first-name>.txt` file.
5. In the right-hand pane, you should see the edits you made.
    * Additions in green.
    * Deletions in red.
6. For each edit hunk, press the *Stage hunk* button.
    * Depending on how close your addition and deletion are to each other, you may have a single hunk or two separate hunks.
    * Notice that the `<your-first-name>.txt` file moves from the *Unstaged files* pane (lower middle pane) to the *Staged files* pane (upper middle pane)

Now you are ready to commit these edits.


## Task 6: Commit edits

1. In SourceTree, switch to File Status view (click the *View|File Status View* menu choice, or press *Ctrl+1*)
2. At the bottom, type in a *Commit message* describing the edits.
3. Click the *Commit* button.

Now you are ready to view a log of your edits.

### Suggested guidelines for commit messages

Commit messages should

* Use a **verb-object** structure
    * Good: *Add LaTeX file for my poster*
    * Bad: *The LaTeX file for my poster was added*
* Use verbs in the **present tense**
    * Good: *Add*
    * Bad: *Added*
* Answer **what** and **why**
    * No need to answer **how**, **when**, or **who**; these are automagically tracked by git
    * Good: *Add LaTeX file for my poster per Ben's request*
    * Bad: *I added lines 22-24 to the LaTeX file for my poster on 2015-04-15*
* Use easily **searchable and specific keywords**
    * Good: *Increase the number of ICD-9 codes used from 4 to 13*
    * Bad: *Make changes to the files*


## Task 7: View log

1. In SourceTree, switch to Log view (click the *View|Log View* menu choice, or press *Ctrl+2*).
    * The top half shows the entire history of the project.
    * Each row represents a discrete commit.
    * At the right, the date, author, and commit ID are shown.
2. Click on another row in the log.
    * The bottom half shows what changes were made from the previous commit to the highlighted commit.

Now you are ready to stage and commit discrete sets of edits.


## Task 8: Stage and commit discrete sets of edits

It's good practice to stage and commit discrete edits.

* Good: *Add linear regression model stratifying by gender*
* Bad: *Add linear regression model, recode geography variable, make histograms, do a whole bunch of other stuff*

Or as [Carlisle Rainey](https://github.com/carlislerainey/git-for-political-science/blob/master/git.md) put it:

> You need to describe the change in a short commit message, so something like
> "add robustness check removing Alaska" or "rewrite the introduction" are good
> changes. If you notice something else to fix along the way, make a note of it
> and continue with your current update. Fix the other problem in a separate
> commit. It is extremely tempting to start fixing every problem you see. If you
> do this, you risk losing track of problems that have been completely fixed, partial
> fixed, and need to be fixed later. A more deliberate, one-at-a-time approach
> is better.

1. Edit the text file `H:\gitSandbox\<your-first-name>.txt`.
    * Add a line **at the beginning** of the file.
    * Add a line **at the end** of the file**.
2. Save the file.
3. In SourceTree, switch to File Status view (click the *View|File Status View* menu choice, or press *Ctrl+1*).
4. In the lower middle pane labeled *Unstaged files*, click the `<your-first-name>.txt` file.
5. In the right-hand pane, you should see the edits you made.
    * Additions in green.
    * Deletions in red.
6. Stage the hunk at the **beginning** of the file
7. Commit this edit.
8. Stage the hunk at the **end** of the file
9. Commit this edit.
10. View the log (click the *View|Log View* menu choice, or press *Ctrl+2*).

Now you are ready to pull and push your commits.
