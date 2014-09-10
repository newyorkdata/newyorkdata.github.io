

# NYDC Website

http://nydata.co


## Development

**The master branch of this repo is what is pushed to nydata.co. Don't mess with the master branch.**

To develop, pull the latest autopages branch `git pull`, and check it out: `git checkout autopages`.

Changes that you make to the autopages branch in the jade files, scss files are automatically compiled when they get checked into the repo. To test your local changes,
make sure you have dependencies installed (`npm install`), and then run `gulp`.

Open http://localhost:8000

If everything looks okay, `git commit` and `git push origin autopages`.



