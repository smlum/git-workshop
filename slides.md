---
title: Intro to git
---

<!-- style stuff -->

<style type="text/css">

  body {
    background-color: #0c0032
  }
  
.container{
    display: flex;
}
.flex-col{
    flex: 1;
}

h1, .white {
  color: white !important;
}

h2, h3, .highlight {
  color: #df61a8 !important;
}

.author {
  color: #df61a8 !important;
}

.avatar {
    height: 120px;
    margin: 0px !important;
}

img {
  border: 0px !important;
  background: rgba(255, 255, 255, 0) !important;
}

li, p {
  color: rgba(255, 255, 255, 0.9);
  font-size: 0.7em !important;
}

.secondary {
  color: rgba(255, 255, 255, 0.45)
}

h4 {
  text-transform: lowercase !important;
  font-size: 0.5em !important;
  position: fixed !important;
  bottom: 0px;
  margin-bottom: 10px !important;
  color: rgba(255, 255, 255, 0.6) !important;
  left: 50%;
  margin-left: -212px !important;
}

a {
  color: #f0afd4 !important;
}

/* this is just title page slide info text - to get around adding a class to mixed markdown text. Note should raise this as an issue on reveal md */

</style>


# intro to git

<img src="images/sam-git-pink.png"> <!-- .element: class="avatar" -->

#### slides at: [samfredlumley.github.io/git-workshop](https://samfredlumley.github.io/git-workshop/) 

---

### We will...

*  Set up a project on GitHub <!-- .element: class="fragment" -->
*  Use git through the command line <!-- .element: class="fragment" -->
*  Host a website using GitHub Pages <!-- .element: class="fragment" -->

---


![alt text](images/version2.jpeg "version nightmare 1")


---

### Git 

*  keep track of files in a project <!-- .element: class="fragment" -->
*  merge content from different people <!-- .element: class="fragment" -->

<hr> <!-- .element: class="fragment" -->

### GitHub  <!-- .element: class="fragment" -->

*  a web service to store files <!-- .element: class="fragment" -->
*  git behind the scenes <!-- .element: class="fragment" -->
*  a place to chat about issues <!-- .element: class="fragment" -->

---

### 🏃‍♀️ activity 

*  login to <!-- .element: class="fragment" --> [GitHub](https://www.github.com)
*  create a "repository" <!-- .element: class="fragment" -->
*  "commit" a change <!-- .element: class="fragment" -->
*  create a "branch" <!-- .element: class="fragment" -->
*  make a "pull request" <!-- .element: class="fragment" -->
*  "fork" another repo <!-- .element: class="fragment" -->
    *  [github.com/fungituser/my-site ](https://github.com/fungituser/my-site )
*  create an "issue" <!-- .element: class="fragment" -->

---

## part 2

Using git locally <!-- .element: class="fragment fade-in-then-semi-out" -->

aka hacking the mainframe <!-- .element: class="fragment" -->

---
<!-- .slide: data-background="images/heart.png" -->
---

### UNIX commands:

```bash
$ clear # clean up the screen 
``` 
<!-- .element: class="fragment" -->

```bash
$ pwd # print working directory (where are we?)
``` 
<!-- .element: class="fragment" -->

```bash
$ ls # list the stuff in current directory 
``` 
<!-- .element: class="fragment" -->

```bash
$ cd <directory> # choose (go to) a directory 
``` 
<!-- .element: class="fragment" -->

```bash
$ cd .. # go back a directory 
``` 
<!-- .element: class="fragment" -->


---

### Setting up

*  [Install git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) 
*  Open Terminal (Mac) or Command Line (Windows)
*  Tell git who you are:

```bash
$ git config --global user.name "Justin Trudeau"
$ git config --global user.email "jtno1@hotmail.com"
```

---

### git commands:

```bash
$ git clone <url> # create a local copy of a remote repo 
``` 
<!-- .element: class="fragment" -->

```bash
$ git add -A # add altered files to staging area
``` 
<!-- .element: class="fragment" -->

```bash
$ git commit -a -m “message” # commit with a reason 
``` 
<!-- .element: class="fragment" -->

```bash
$ git push origin master # push changes back to remote 
``` 
<!-- .element: class="fragment" -->

```bash
$ git pull origin master # pull changes to local 
``` 
<!-- .element: class="fragment" -->

---

### 🏃‍♀️ activity 

*  <!-- .element: class="fragment" -->  "`cd`" to your desktop in terminal 
*  <!-- .element: class="fragment" --> "`clone`" your remote repository 
*  <!-- .element: class="fragment" --> edit "`portfolio.txt`" in a text editor 
*  <!-- .element: class="fragment" --> "`add`" and "`commit`" the changes 
*  <!-- .element: class="fragment" --> "`push`" the changes back to remote 

---

## part 3

Let's make a website

---

### what is a website? <!-- .element: class="white" -->

[example.com](https://example.com/) <!-- .element: class="fragment" -->

---

### 🏃‍♀️ activity 

*  <!-- .element: class="fragment" --> change the name of "`portfolio.txt`" to "`index.html`"  
*  go to settings > GitHub Pages <!-- .element: class="fragment" -->
*  publish by selecting the master branch as source <!-- .element: class="fragment" -->
*  fork this repo: <!-- .element: class="fragment" -->
    *  [github.com/samFredLumley/folio](github.com/samFredLumley/folio)
*  publish on github pages like before <!-- .element: class="fragment" -->
*  make some edits to <!-- .element: class="fragment" --> "`index.html`"

---

### Thanks!

---

### links <!-- .element: class="white" -->

*  [Great YouTube tutorial](https://www.youtube.com/watch?v=BCQHnlnPusY)
*  [Reference for git commands](http://rogerdudler.github.io/git-guide/)
*  [Example of a git workflow](https://nvie.com/posts/a-successful-git-branching-model/)


