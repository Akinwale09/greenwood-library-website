# Captone Project: Enhancing a Community Library Website

### Bacground Scenario

Been part of a development team tasked with enhancing the website for the "Greenwood Community Library". The website aims at be more engaging and informative for its visitors. Its currently includes basic section: Home, About US, Events, and Contact US. My team decided to add a "Book Reviews" section and update the "Events" page to feature upcoming community events. 

I will simulate the roles of two contributors: "Morgan" and "Jamie". Morgan will focus on adding the "Book Reviews" section. while "Jamie" will update the "Events" page with new community events. 

## Objectives

- Practice cloning a repository and working with branches in git.
- Gain experince in stagging, commiting, and pushing changes from both developers.
- Create pull requests and merge them after resolving any potential conflicts.

## Setup

1. Create a repository on GitHub:

  - Name it greenwood-library-website.

    ![repo](./img/1.reponame.png)

  - Initialized it with a README.md file and clone it to my local machine. 

    ![repocreate](./img/2.RepoCreated.png)

    ![cloningURL](./img/3.httptocopyrepo.png)

    ![cdtoclone](./img/4.cdtoCapStoneDirectory.png)

    ![cloneProject](./img/5.clonethegreenwordProject.png)


## Tasks

1. In the main branch, using Visual Studio code editor, I will ensure there are files for each of the web pages.

    - home.html
    - about_us.html
    - events.html
    - contact.html

  ![htmlfile](./img/6.htmlfiles.png)

 
2. I will add random content into each of the files. 
    ![home](./img/7.home.png)

    ![about](./img/8.about.png)

    ![event](./img/9.event.png)

    ![contact](./img/10.contactus.png)



3. I will stage, commit, and push the changes directly to the main branch. 

   `git status`

  ![status](./img/11.status.png)
  
   `git add`

   ![gitadd](./img/12.gitadd.png)

   `git commit -m "message"`

   ![commit](./img/13.commit.png)

   `git push`

   ![push](./img/14.push.png)


### Morgan's Work: Adding Book Reviews  

1. I will create a Branch for Morgan
  
    `git checkout -b add-book-reviews`

   ![morganbranch](./img/15.morganbook.png)

2. Swicth to a new branch name add-book-reviews

   ![morganswitch](./img/15.morganbook.png)

3. Add a new file "book_reviews.html" to represent the book reviews sections:
 
     `touch book_review.html`
   ![createfile](./img/16.bookreviewfileadded.png)

4. Add a random text content into the file

    ![randomtext](./img/17.randomtextaddedformorgan.png)

5. Stage, commit, and push chnages with a message "Add book reviews sections."
  
     `git status`

    ![morganStatus](./img/18.MorganStatus.png)

     `git add .`

    ![](./img/19.MorganAdd.png)

    `git commit -m "message"`

    ![morgancommit](./img/20.MorganCommit.png)

    `git push`

6. Push the "add-book-review" branch to GitHub

    ![Morganpush](./img/21.morganpush.png)


7. Raise a PR (Pull Request) for Morgan's work

    ![morganPR](./img/22.morganPR.png)

8. Merge Morgan's work to the main branch.

     ![morgansmerge](./img/23.Morganmerge.png)

     ![merged](./img/24.Merged.png)

### Jamie's Work: Update Event Pages

We would repat thesame flow for Jamie's work on Events pages. we would ensure Jamie's work is in "update-events" branch. 

