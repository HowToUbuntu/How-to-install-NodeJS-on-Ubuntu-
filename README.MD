How to install NodeJS on Ubuntu!

---
# Option 1: Installing Node.js with Apt from the Default Repositories

Ubuntu 20.04 contains a version of Node.js in its default repositories that can be used to provide a consistent experience across multiple systems.

> Warning: the version of Node.js included with Ubuntu 20.04, version 10.19, is now unsupported and unmaintained. You should not use this version in production, and should refer to one of the other sections in this tutorial to install a more recent version of Node.

To get this version, you can use the apt package manager. Refresh your local package index first by typing:
```
$ sudo apt update
```
Then install Node.JS
```
$ sudo apt install nodejs
```
Check that the install was successful by querying node for its version number:
```
$ node -v
```
### Output
```
v10.19.0
```

---

If the package in the repositories suits your needs, this is all you need to do to get set up with Node.js. In most cases, you’ll also want to also install npm, the Node.js package manager. You can do this by installing the npm package with apt:

```
$ sudo apt install npm
```

This will allow you to install modules and packages to use with Node.js.

At this point you have successfully installed Node.js and npm using apt and the default Ubuntu software repositories. The next section will show how to use an alternate repository to install different versions of Node.js.


#Please comment any suggestions or if it worked!