# Intro to JS

## Intro to JS Talk (30 - 45 min)
All about font-end.

## Rantly Demo (30min)

### UI / UX
* Realtime with short polling
* Two way data binging in rant
* Client & server side validation
* CSS Animations
* User avatars with gravatar
* Single page & one initial load

### Code
* Rails API
* Two repos
* Styleguide: Custom CSS, RWD, web components
* JavaScript all the things
* Ember packages
* Sass

## Node Install Fest (30min)

Make sure you are using the latest version of brew.
```
$ brew update
```

Confirm there are no major brew configuration errors.
```
$ brew doctor
```

Install Node.js!
```
$ brew install node
```

This install will give you Node & NPM. Confirm both are working with the `-v` flag.

```
$ node -v
=> v0.10.34

$ npm -v
=> 2.1.14
```

Now you may use NPM to install Ember. Don't forget to use the -g flag. This installs the package globally.

```
npm install -g ember-cli
```
_Note_: This should NOT require you to use `sudo`. If you get an EACCESS error, please let me know.

Now you have the `ember` binary to use in any directory, just like rails. Confirm is is installed.

```
$ cd workspace
$ ember new cats
$ cd cats
$ ember serve
```
This should serve your application. Visit http://locahost:4200 to confirm.

### Resources

[Install without Sudo](http://www.wenincode.com/installing-node-jsnpm-without-sudo/)
