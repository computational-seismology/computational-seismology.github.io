# computational-seismology.github.io

Please, push your modifications to the ```gh-pages``` branch. The ```master``` branch
is used to publish the generated website.

:warning:
Once again, don't push your modifications straight to the master branch.
:warning:

To contribute, clone this repo (or your fork):
```
git clone https://github.com/computational-seismology
```

Follow the instructions on [hugo
documentation](https://gohugo.io/hosting-and-deployment/hosting-on-github/).
Since, github forces us to publish from the ```master``` branch, invert
```master``` and ```gh-pages``` wherever they appear in the text written in the 
previous link.

Once the repo is setup, generating the website and pushing it to the
```master``` branch is done by:
```
# Regenerate the public folder and commit it
./commit-gh-pages-files.sh
# Push to the tracked master branch
git push upstream master
```

Don't forget to also bring your modifications to the ```gh-pages``` branch:
```
# Push the modifications you
git commit -a -m "My awesome commit message"
git push upstream gh-pages
```
