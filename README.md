Research Group Web Site Template
================================

Local build
---------

```
python -m venv venv
. ./venv/bin/activate
pip install -r requirements.txt
make
make serve
```

Publication List
----------------

The list of publications is in `bib/pubs.bib`. Typing `make` will generate `pubs.html`, which contains a pretty, sorted HTML-formatted list of papers. The public page, `publications.html`, also has a link to download the original BibTeX.

Building
--------

The requirements for building the site are:

* [Jekyll][]: run `gem install jekyll`
* [bibble][]: available on `pip`
* ssh and rsync, only if you want to deploy directly.

`make` compiles the bibliography and the website content to the `_site`
directory. To preview the site, run `jekyll serve`` and head to
http://0.0.0.0:5000.


Deploying to Your Sever
-----------------------

To set up deployments, edit the Makefile and look for the lines where `HOST` and `DIR` are defined. Change these to the host where your HTML files should be copied to.

To upload a new version of the site via rsync over ssh, type `make deploy`. A web hook does this automatically when you push to GitHub. Be aware that the Makefile is configured to have rsync delete stray files from the destination directory.

[Jekyll]: http://jekyllrb.com/
[bibble]: https://github.com/sampsyo/bibble/
