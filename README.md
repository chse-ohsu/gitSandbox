# gitSandbox
Sandbox to play with git and SourceTree

## Task 1: Get git GUI

1. Download and install [SourceTree](http://www.sourcetreeapp.com/).
2. Click the *Tools|Options* menu choice.
3. In the *General* tab,
  * Change the *Default user information* to your name and email address.
  * Change the *Project folder* in the *Misc* section to `H:\`.
4. Click *OK*.
5. Now you are ready to clone a repository.


## Task 2: Clone an existing repository

1. Click the *Clone/New* icon on the toolbar (*Ctrl+N*).
2. Click the *Clone Repository* tab.
3. In the *Source Path/URL* text box, enter  
    [`X:/OHSU Shared/Restricted/OCHSER/Resources/Code_Sharing/gitSandbox.git`](file:///X:/OHSU%20Shared/Restricted/OCHSER/Resources/Code_Sharing/gitSandbox.git/).
4. Confirm that the *Repository Type* says `This is a Git repository`.
5. Confirm that the *Destination Path* is `H:\gitSandbox`. This will create a folder named `gitSandbox` in the *Project folder* you assigned earlier.
5. Click the *Clone* button.
6. Navigate to the [`H:\gitSandbox`](file:H:/gitSandbox/) folder (click the link) and confirm that you have the files listed [here](https://github.com/benjamin-chan/gitSandbox) (you may not see `.gitignore`; if you don't, don't worry, it's there but hidden).
7. Now you are ready to create and stage a new file.


## Task 3: Stage a new file

1. Using a text editor (e.g., Notepad, [Notepad++](http://notepad-plus-plus.org/), [Sublime](http://www.sublimetext.com/), [Atom](https://atom.io/)), create a text file.
    * Fill the text file with a bunch of text.
    * Or copy-paste the contents of another text file into this empty file.
    * If don't feel creative, use a random text generator, like [Lorem Ipsum](http://www.lipsum.com/).
2. Save the file as `H:\gitSandbox\<your-first-name>.txt`.
3. In SourceTree, switch to File Status view (click the *View|File Status View* menu choice, or press *Ctrl+1*)
4. In the lower middle pane labeled *Unstaged files*, check the box next to your `<your-first-name>.txt` file.
    * Notice that the `<your-first-name>.txt` file moves from the *Unstaged files* pane (lower middle pane) to the *Staged files* pane (upper middle pane)
5. Now you are ready to commit this addition.


