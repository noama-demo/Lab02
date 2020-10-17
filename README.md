# Lab-02
## Exercise 1 - Checkout and Branching
### Overview
In this exercise, we will work with branches  
We will first view branches and their content and then create our own branch and commits

#### <u>Cloning a repo</u>
- Go to a playground folder using explorer (c:\temp, for example)
- Right click inside the folder and select 'GitExt Clone...'
- Paste the URL C:\GitServer\labs\Lab02-ex1 and choose clone
- Right click inside/on the folder and select 'GitExt open repository'

#### <u>Reviewing branches content in workspace</u>
- On the left pane, right click master branch and select Checkout
- <b>Tip</b>: You can use the File Explorer button on the Button Bar to open explorer
- View the following files using your editor of choice (notepad)
    1. <i>gitDemo\ClassA.cs</i>
    2. <i>gitDemo\ClassB.cs</i>
- On the left pane, right click <i>feature/featureA</i> branch and select Checkout
- View the following files using your editor of choice (notepad)
    1. <i>gitDemo\ClassA.cs</i>
    2. <i>gitDemo\ClassB.cs</i>
- On the left pane, right click <i>feature/featureB</i> branch and select Checkout
- View the following files using your editor of choice (notepad)
    1. <i>gitDemo\ClassA.cs</i>
    2. <i>gitDemo\ClassB.cs</i>

#### <u> Reviewing branches content inplace </u>
- On the history pane, click master branch commit
- View the following files in the Split View -> File Tree
    1. <i>gitDemo\ClassA.cs</i>
    2. <i>gitDemo\ClassB.cs</i>
- On the history pane, click <i>feature/featureA</i> branch commit
- View the following files in the Split View -> File Tree
    1. <i>gitDemo\ClassA.cs</i>
    2. <i>gitDemo\ClassB.cs</i>
- On the history pane, click <i>feature/featureB</i> branch commit
- View the following files in the Split View -> File Tree
    1. <i>gitDemo\ClassA.cs</i>
    2. <i>gitDemo\ClassB.cs</i>

#### <u> Create branch and commit </u>
- On left pane, select master branch, right click it, and select 'Create Branch'
- Name the branch feature/myfeature and press 'Create Branch'
    ```
    Note: Notice that the master branch and your new branch are on the same SHA1
    ```
- Make a change to <i>gitDemo\ClassA.cs</i> using your favorite editor outside of GitExtension
- Commit your changes
    1. On the Button Bar, Press the Commit icon
    2. Add the relevant files to stage using the purple arrows (stage/unstage)
    3. Add any explaining message
    4. Click commit

#### <u> Mail the results </u>
- To: <TBD>
- Topic: checkout and branches
- Body: The diff between your new feature and master
