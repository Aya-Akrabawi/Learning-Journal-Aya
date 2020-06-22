## Git Tutorial: Part 1:

**Git** is Aa free and open source DVCS (distributed version control system) that has snapshot feature that when you make any changes on you project version and commit it, Git creates a snapshot of the file and stores a reference to it.

**what can Git do?**
1. Snapshots
as we mentioned in the definition.

2. Local Operations:
that is the project’s history resides on the local disk, which allows fors process expediency. 

3. Tracking Changes: Git tracks every single change applied to any file or directory and detect file corruptiom or loss of information in transit.

4. Loss of Data: with Git, your suffering from irreversible damage to files will be decrease as Git set up to minimize that.

5. States: Files in Git can stay in three main states:
    - Committed: Data is securely stored in a local database
    - Modified: File has been changed but not committed to the database.
    - Stage: Flagged a file’s changed version to be committed in the next snapshot

**please check the image**
![https://blog.udemy.com/wp-content/uploads/2015/08/image066.png](state)

**Getting Started**
- Follow thi link to download:
   - [http://git-scm.com/download/win](windows)
   - [http://git-scm.com/download/linux](Linux) 
   or For Fedora:
        ``` $ sudo yum install git ```
    For Ubuntu:

     ``` $ sudo apt-get install git ```
   - [http://git-scm.com/download/mac](Mac OS X)

##Seeing Your Remotes:


- There is a command called ``` git remote ``` >> to view the short names, such as “origin,” of all specified remote handles.

- you can add -v to git remote ``` git remote -v ``` >> to view all the remote URLs next to their corresponding short names.

**example**
``` $ cd example

$ git remote -v

remote1 https://github.com/remote1/example (fetch)

remote1 https://github.com/remote1/example (push)

remote2 https://github.com/remote2/example (fetch)

remote2 https://github.com/remote2/example (push)

remote3 https://github.com/remote3/example (fetch)

remote3 https://github.com/remote3/example (push)
```
