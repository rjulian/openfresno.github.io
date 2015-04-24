[![Stories in Ready](https://badge.waffle.io/codeforhawaii/codeforhawaii.org.png?label=ready&title=Ready)](https://waffle.io/codeforhawaii/codeforhawaii.org)
# Code for Hawaii Website

Our website @ http://codeforhawaii.org

## Want to help out?

- Clone this repo.

There are two ways to install this website on your machine and help out with
development. If you're concerned with polluting your environment with
application libraries and have Virtualbox / Vagrant installed, then use
Vagrant instructions, otherwise, use the Local instructions.

### Vagrant

If you're on your development machine and want to use vagrant to isolate your
dependencies/workspace, we've included a Vagrantfile to help you get started.

Run the following command:

`vagrant up`

Once the vagrant instance is up, open your browser to:

`open http://127.0.0.1:4000`

You'll be able to edit the files from the clone and see the changes

### Local

- `gem install jekyll`
- `jekyll serve`
