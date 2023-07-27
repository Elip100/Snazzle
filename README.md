This is the branch to create stable releases from. Every once in a while, I'll make one of these, which is essentially a frozen version of `main` that's stable to use as a release branch.

# Snazzle
A better frontend for Scratch, built by the community, for the community

Snazzle is my attempt at a better Scratch website. It aims to be feature-rich and easy and quick to use, incorporating many things that the Scratch community has been wanting for years.

Basically, this is a Scratch website just for <s>MagicCrayon9342</s> power users.

> If you're more than a casual user of the Scratch website for whatever reason, then you'll like Snazzle.
> It's like a giant vat of coffee brewed with ingredients from the Scratch community.
-- Snazzle's website

## Running your own instance locally
Since Snazzle is very much still in development, this won't be representative of the final product's build steps.

But for now, this is how you do it:
1. Clone the repo
2. (optional but recommended) Create a Python virtual environment. We recommend Python 3.11 or later.
3. Run `pip3 install -r requirements.txt`.
   > If you are on an Arch based linux distro, you will have to run "sudo pacman -S python-flask
4. Once deps are installed, run `python3 main.py`. This will set up a Flask server at `127.0.0.1:3000`. If you find any bugs, please report them.
   > If you're on Windows, run `py main.py` instead.
5. Go to `127.0.0.1:3000` in your favourite browser and play around with it!

## Hosting on Replit
Just Import from Github. In the future, you'll have to enable a variable called `REPLIT_MODE` at the very top of `main.py`.
