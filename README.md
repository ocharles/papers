papers
======

A Git annex repository of academic papers. The intention here is to both provide myself with backups and easy access to papers, while also collecting a repository of links so that people can *always* find the paper they are looking for.

Using this
==========

To use this repository you need to have Git and Git Annex installed. Then:

    git clone git://github.com/ocharles/papers
    git annex init local-copy
    git annex get .
    
This will download all of the papers I have. You can of course just selectively `git annex get` the papers that interest you.

To stay up to date, just run

    git annex sync origin

Alternatively, if you are running the git annex assistant, click on the top right, choose `add another local repository` and select the directory you cloned the repo into.  It will then be automatically kept up to date by the assistant
