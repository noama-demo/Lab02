# Lab-02
## Exercise 1 - Checkout and Branching

#### Cloning a repo
- Go to a playground folder using explorer (c:\temp, for example)
- Right click inside the folder and select 'GitExt Clone...'
- Paste the URL https://github.com/noama-demo/Lab02-ex1.git and choose clone

#### Reviewing branches content in workspace
- On the left pane, right click master branch and select Checkout
- View the following files using your editor of choice (notepad)
    1. Lab-02-ex1\gitDemo\ClassA.cs
    2. Lab-02-ex1\gitDemo\ClassB.cs

- On the left pane, right click feature/featureA branch and select Checkout
- View the following files using your editor of choice (notepad)
    1. Lab-02-ex1\gitDemo\ClassA.cs
    2. Lab-02-ex1\gitDemo\ClassB.cs

- On the left pane, right click feature/featureB branch and select Checkout
- View the following files using your editor of choice (notepad)
    1. Lab-02-ex1\gitDemo\ClassA.cs
    2. Lab-02-ex1\gitDemo\ClassB.cs

#### Reviewing branches content inplace
- On the history pane, click master branch commit
- View the following files in the Split View -> File Tree
    1. Lab-02-ex1\gitDemo\ClassA.cs
    2. Lab-02-ex1\gitDemo\ClassB.cs

- On the history pane, click feature/FeatureA branch commit
- View the following files in the Split View -> File Tree
    1. Lab-02-ex1\gitDemo\ClassA.cs
    2. Lab-02-ex1\gitDemo\ClassB.cs

- On the history pane, click feature/FeatureB branch commit
- View the following files in the Split View -> File Tree
    1. Lab-02-ex1\gitDemo\ClassA.cs
    2. Lab-02-ex1\gitDemo\ClassB.cs

#### Create branch and commit
- On left pane, select master branch, right click it, and select 'Create Branch'
- Name the branch feature/myfeature and press 'Create Branch'
    ```
    Note: Notice that the master branch and your new branch are on the same SHA1
    ```
- Make a change to Lab-02-ex1\gitDemo\ClassA.cs using your favorite editor outside of GitExtension
- Commit your changes
    1. On the Button Bar, Press the purple Commit icon
    2. Add the relevant files to stage using the purple arrows (stage/unstage)
    3. Add any explaining message
    4. Click commit

#### Mail the results
- To: <TBD>
- Topic: checkout and branches
- Body: The diff between your new feature and master
