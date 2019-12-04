# Git for Web Development Project
In this project you will be using the concepts learned in the Git for Web Development lesson to fork/clone/push/and submit a PR for each project during this sprint.

This project consists of two parts:

## Part One:
You will need to follow the Lambda School Git Workflow to add a file to this project follow the steps below:

- [ ] Create your own version of this repo - Fork
- [ ] Add your TL as a collaborator
- [ ] Clone this repo
- [ ] Create a branch `git checkout -b 'firstName-lastName'`
  - [ ] Add a file to the project called `yourFirstName-yourLastName`.txt. This should contain the link to your completed codepen from part 2 as well as the review questions/answers
  - [ ] Run your usual git commands for adding/committing and pushing **Be sure to push to your branch!**
- [ ] Create a Pull-Request to submit your work
  - [ ] Use your own student fork as the base (compare across forks, base-fork -> master).
  - [ ] Add your TL as a reviewer on the Pull-Request
- [ ] TL then will count the Assignment as done by merging the HW back into master "STUDENT FORK".

## Part Two:
1. fork this codepen https://codepen.io/BritHemming/pen/eYYEoPa?editors=1100
2. You will be marking up all of the HTML and styling it to look like this: https://codepen.io/BritHemming/full/jONmxOm using CSS
* this should be review from yesterday/ extra practice
3. After you are finished please copy the review questions into your .txt file and answer them
4. don't forget to add, commit and push your changes.


    1. What is Semantic HTML? 

       Semantic HTML is the correct use of HTML to reinforce the meaning of content on a web page, rather than merely define its appearance.

    2. What is HTML used for? 

      HTML defines the structure and layout of a Web document by using a variety of tags and attributes. 

    3. What is an attribute and where do we put it? 

      Attributes provide additional information about HTML elements.
      Attributes are always specified in the start tag of the element we are using. 
      Example: <img src="attribute"> or < p title="the Attribute> or < p style ="color:red attribute>

    4. What is the h1 tag used for? How many times should I use it on a page?

       The h1 tag is usually use for the title of a page and it is the first header visible on a page.
       It is important to understand that there should be only one h1 tag per page.
       This is because it makes more sense and this is what we should aim for.

    5. Name two tags that have required attributes

      The img tag and the <a> tags

    6. What do we put in the head of our HTML document? 

      Inside we have <meta> tags & the <title> tag
     
    7. What is an id? 

    The id selector uses the id attribute of the HTML element, and is defined with a "#". 

    8. What elements can I add an id to? 
       You can add id to any element.
     

    9. How many times can I use the same id on a page? 
     you can give an id value to one and only element as this will be the unique one in the whole page. 

    10. What is a class? 
       A class is a blueprint that defines the variables and the methods common to all objects of a certain kind.
    11. What elements can I add a class to? 
        You can add class to any element.
    12. How many times can I use the same class on a page? 
       we can use the same class more than once as long as it is valid. An invalid however document means that have duplicated ids.

    13. How do I get my link to open in a new tab?
         In an anchor element insert a target attribute such as target="_blank".
    14. What is the alt attribute used for? 
       the alt attribute specifies an alternate text for an image, if the image cannot be displayed.
       It provides alternative information of an image if the user for some reason it cannot displayed it.

    15. How do I reference an id?
         #

    16. What is the difference between a section and a div
        
        The <section> tag defines sections in a document, such as chapters, headers, footers, or any other sections of the document. ... The <div> tag defines a division or a section in an HTML document. The <div> tag is used to group block-elements to format them with CSS.

        

    17. What is CSS used for? 
         Cascading Style Sheet is the language to describe the presentation of web pages , including colors, layouts and fonts. It allow as to adapt the presentation to different types of devices, like tablets, mobiles etc.

    18. How to we select an element? Example - every h2 on the page

       Each HTML element—<h1>, <p>, <li>, <body>and any other HTML element can be selected with CSS by using the tag name without the angle brackets (< and >). For example, you can select all of the <p> tags in your webpage by using the element selector p. 

    19. What is the difference between a class and an id? - Give me an example of when I might use each one
         
         the class selector is a name proceded by a period (.) and an ID selector is a name proceded by a (#). The difference between them is that id can be used to identify one element and class can be used to identify more than one.

    20. How do we select classes in CSS?
        
        class selector selects elements with a specific class attribute. To select elements with a specific class, write a period (.) character, followed by the name of the class.

    21. How do we select a p element with a single class of “human””?
       p.human

    22. What is a parent child selector? When would this be useful? 
   
      Means selecting child elements inside of parent-parent selector.

    23. How do you select all links within a div with the class of sidebar?

       div a.sidebar

    24. What is a pseudo selector?
       a pseudo selector is a selector element with a specific state.


    25. What do we use the change the spacing between lines?
       Using the Line-Height attribute.

    26. What do we use to change the spacing between letters?
        Using letter-spacing increase or decrease the space between the characters.

    27. What do we use to to change everything to CAPITALS? lowercase? Capitalize?
        
        div.a {
           text-transform: lowercase;
        }

        div.a {
            text-transfrom: uppercase;
        }

    28. How do I add a 1px border around my div that is dotted and black?
        < div style="border: dotted 1px black" id="mydiv">

    29. How do I select everything on the page? 
        * 

    30. How do I write a comment in CSS?
        /* comments */

    31. How do I find out what file I am in, when I am using the command line? 
        pwd

    32. Using the command line - how do I see a list of files/folders in my current folder?
        ls 

    33. How do I remove a file via the command line? Why do I have to be careful with this? 
        in the command line type del/f filename the file you want to delete using commas.

    34. Why should I use version control? 
        Version control helps team to solve their problems, tracking down the changes and helping prevent conflicts.
    35. How often should I commit to github?

       we need to commit our code regularly and meaningfully. This helps both as and our TL leader.
        
    36. What is the command we would use to push our repo up to github? 

        git push origin 'firstName-LastName

    37. Walk me through Lambda's git flow. 
        1. Create YOUR OWN version of Repo (Fork)
        2. Add your TL as collaborator
        3. Clone your Repo (in your computer at your vs editor: git clone <repo-address>)
        4. Create a branch(cd repo project, git checkout -b 'your name')
        5. Push your new branch to the Git Hub (git push origin firstName lastName)
           on GitHub: compare & pull request----> base: your and not github master
        6. Add TL as reviewer(if he has accept already your invitation he will merge the work in to your master reviewed and approved it).



## Stretch
Stretch Review questions: 
    1. What is the difference between an inline element and a block element?

    Block-level elements take up all of the available space within their parent container.

    Inline elements can exist within block-level elements.

    2. What happens when an element is positioned absolutely? 

    It is positioned automatically to the starting point (top-left corner) of its parent element.

    3. How do I make an element take up only the amount of space it needs but also have the ability to give it a width? 


    4. Name 3 elements that are diplay block by default, 2 elements that are display inline by default and 1 element that is display inline-block by default
     
     1.The <div> element is a diplay block by default element.
     2.The <header> element is a diplay block by default element.
     3.The <footer> element is a diplay block by default element.  

     1. The <button> element is display inline by default element.
     2. The <input> element is display inline by default element.

     1. The <span> element is a display inline-block by default element.

    5. In your own words, explain the box model. What is the fix for the box model? 

    The box model is the primary layout of everything in the web. It describes the layout in rectangular boxes, which every sinlge element is in a box. Using the box model, web developers can use a lot of varieties of properties, such as padding, margin, borders to create other pages.
Stretch Git Tasks
- [ ] While the processes learned here will set you up to be successful in most situations, they are just the tip of the iceberg in learning Git. Independently research the following topics to learn more about Git.

  - [ ] Research and understand what a `merge conflict` is and how to resolve it.
       To resolve a merge conflict caused by competing line changes, you must choose which changes to incorporate from the different branches in a new commit.

       You must resolve this merge conflict with a new commit before you can merge these branches.
       1.Open Git Bash.
       2.Navigate into the local Git repository that has the merge conflict.
       (cd repository-name).
       3.Generate a list of the files affected by the merge conflict.
       4.Open your favorite text editor such as VSCode and navigate to the file that has merge conflicts.
       5.Search the file for the conflict, to see the beginning of the merge conflict in your file.
       6.Devcide if you want to keep only your branch's changes, keep only the other branch's changes, or make a brand new change, which may incorporate changes from both branches. 
       7.Add your changes (git add .)
       8.git commit -m'message initial changes'
       9.git push origin firstName lastName.


  - [ ] Research the Git commands `pull`, `rebase`, `merge`. These commands will allow you to bring in changes that other developers push to the master branch.

   Git pull
   The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content.
   Git Rebase
   Means changing the base of your branch from one commit to another making it appear as if you'd created your branch from a different commit. Internally, Git accomplishes this by creating new commits and applying them to the specified base.
   Git Merge
    Means that git merge is  used in conjunction with git checkout for selecting the current branch and git branch -d for deleting the obsolete target branch.

  - [ ] Research the Git commands `reset `, `revert`, `clean`. These commands will allow you to go back and amends previous commits you have made.

     Git Reset



     Git Revert
    The git revert command is used for undoing changes to a repository's commit history. Other 'undo' commands like, git checkout and git reset , move the HEAD and branch ref pointers to a specified commit. Git revert also takes a specified commit, however, git revert does not move ref pointers to this commit.
     Git Clean
      Remove only files ignored by git. This may be useful to rebuild everything from scratch, but keep manually created files.
    To remove directories yu follow the steps:
    1.To remove directories, run git clean -f -d or git clean -fd.
    2.To remove ignored files, run git clean -f -X or git clean -fX.
    3.To remove ignored and non-ignored files, run git clean -f -x or git clean -fx.

- [ ] Research and set up a Graphical User Interface (GUI) Git console. 

- [ ] Research and setup SSH keys with GitHub, so that you do not need to input your username/password each time you push. 


