---
layout: page
title: 03_mdSimple
---

## 03_mdSimple ##

simple 1-sheet page from markdown

---
---



## p03s01 ToC ##
- p03s01 ToC
- p03s02 use cases
- p03s03 parameters
- p03s04 playbook
- p03s05 original tutorial notes

---
---

## p03s02 use cases ##

L-info stripped-down uses e.g. OtF page standups


  
---

## p03s03 parameters ##

no index
no Jekyll theme choice
editing the ReadMe.md file
no yaml config file

---
---

spacing

---
---


## p03s04 playbook ##

---

### p03s04a prepro ###

LYSiTaS, ID executable via 16m_nmpm process (rhs = desired end state, lhs = executable)
inventory of required copy items for inclusion

---

### p03s04b build program / executable (00:23:30) ###

create repo
- gH sign in
- new repo
- name repo
- init wi ReadMe
- create repo button

blank the ReadMe
- select ReadMe
- open editor
- manually blank the copy
- comment / commit

edit ReadMe.md index-proxy
- select ReadMe.md
- select 'edit' (pencil icon)
- create or paste md copy in
- comment / commit

build page
- settings
- gitHub Pages
- select source as `master branch`
- save (if applicable)
- refresh till button greens
- select when greened

---
---

### p03s04c post production ###

testback vs rhs (desired end state)

---

## p03s05 original tutorial notes ##

//////////////////////////////////////////////////////////////////////
s02a	:  mdFormat one-sheet (22:00) Auto Theme Chooser (Jekyll, markdown, no-index)
s02b	:  mdFormat multi-sheet (35:20 devLog rework)
//////////////////////////////////////////////////////////////////////
{md jkll-smpl, no-index, no yaml config, no posts}
{md jkll-vrs, no-index, yaml config file, no posts}

s02a	:  mdFormat Auto Theme Chooser (Jekyll, markdown, no-index)

New repo in the poidspace / namespace;  name;  init wi Readme; create

***note no index required;  edit the ReadMe.md file;  pencil (editing) icon

Markdown intro;  plaintext file that can be rendered into markdown

Editing readme in md (29:00);  preview changes;  comment;  commit

Settings, GitHub pages;  Choose a Theme;  select theme;  wait till button turns green;




CREATE REPO,README
(00:38:50) create new repo;  name;  init wi readme;  create repo
***blank out the readme if app***

CREATE CONFIG FILE
(00:39:20) create _config.yml file


From <newRepoName>, create new file (00:40:30) called {_config.yml}

copy/paste from his online example in 3-Jekyll;
https://evanwill.github.io/go-go-ghpages/3-jekyll.html

Starter yaml content;  


<  yc  >
# basic info
title: 2nd multipage test
author: red bullion
email: r3d@redbullion.com
description: attempt to replicate in van same as sf-iteration
twitter_username: tbd+rrtUK
github_username:  rrtUK

# Build settings
markdown: kramdown
theme: minima

< /yc  >
Note:  these are NOT md hashes ergo NOT headers, these are commented out

Checked my original multi-page test again, 100% working as designed wrt links:
https://rrtuk.github.io/multi-page-test/

copy/paste into _config.yml;  then customize; comment,commit (00:45:00);

CREATE GENERIC PAGE (00:46:10)

Copy sample material ‘about.md’ page from
 3-Jekyll  :  https://evanwill.github.io/go-go-ghpages/3-jekyll.html

<  gp  >
---
layout: page
title: 01_about
---

prototypical about page

Reasons:
- c'existe.
- its a test.



< /gp  >

From <newRepoName>, create new file, name it {about.md} or {fileName.md}

Paste in sample material frm above, then customize (00:47:00);  most important -- three dashes ellipsis (---) above and below layout: page and title: <fileName>; comment/commit (00:48:00)

Build site from here (00:49:00), no posts yet but multi auto-gen’d pages 

Settings;  GitHub Pages;  source: master branch;  save (if app); depress button when green





