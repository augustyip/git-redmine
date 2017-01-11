forked from [coiled-coil/git-redmine](https://github.com/coiled-coil/git-redmine)

Git-Redmine

Git-Redmine is integration tool between Git and Redmine, written in Python.


Install

1. Copy git-redmine into /usr/local/bin or whatever directory which can be executable specified by $PATH variable.

2. Configure API key of your Redmine account. API key is found in account menu in the redmine.
$ git config --global redmine.apiKey xxxxxxxxxxxxxxxxxxxxxxxxxxx

3. Configure Redmine URL.
$ git config --global redmine.projectUrl http://YOUR.REDMINE.URL


Tutorial

* List issues which assigned to you(limited latest two sprints)
$ git redmine

* Show details of a issue
$ git redmine 1234
(Note that 1234 is the issue ID, please change it your self)

* Commit using with commit message consist on the issue subject and issue ID
$ git redmine commit 1234

![Git Redmine](https://raw.githubusercontent.com/augustyip/git-redmine/master/Screen%20Shot.png)
