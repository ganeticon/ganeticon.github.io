# ganeticon.github.io
webpage

[![Build Status](https://travis-ci.org/ganeticon/ganeticon.github.io.svg?branch=build)](https://travis-ci.org/ganeticon/ganeticon.github.io)

## build instructions unsing mkdocs
* install mkdocs (i.e. `sudo apt install mkdocs` in debian/ubuntu)
* clone the repo `git clone https://github.com/ganeticon/ganeticon.github.io/`
* change to the project directory `cd ganeticon.github.io`
* start local mkdocs-server `mkdocs serve`
* edit `docs/index.md` and watch the webpage on [http://127.0.0.1:8000](http://127.0.0.1:8000)
* commit your changes and push to remote/github (build branch)
* ~~the webpage will be build by travis-ci and automaticaly published in the master branch~~ (currently broken???)
  * run `mkdocs gh-deploy -v --clean --remote-branch master --remote-name origin`
