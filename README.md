# README-PBfB
PBfB2018

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)



[Example of a link to a PDFfile](/ColorPlot.pdf)


install:
  - sudo pip install proselint

script: 
- proselint my_prose.md

install:
  - sudo apt-get install npm
  - sudo npm install -g markdown-link-check

script: 
- ./check_dead_links

