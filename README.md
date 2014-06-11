# PouchDB Todo Example


## Overview

This is an example PouchDB Todo application with replication to CouchDB. 

While I found a lot of great references that explained various parts of PouchDB, I didn't find a complete example for what I was looking to do. I figured I could learn it best by pulling the details into a little example app. So here you go!

Read the comments of the `index.html` file for details on how this works.

## Preview

You can preview the PouchDB Todo Example on Github Pages here: [kevbaker.github.io/pouchdb_todo_example](http://kevbaker.github.io/pouchdb_todo_example/)


## Dependencies

I put all the HTML, CSS, and Javascript in one file to make it easy to install.

All Javascript and CSS dependencies for this example are loaded through a CDN.

For remote replication to work properly with this example you will need to install a local copy of
[PouchDB](http://couchdb.apache.org) and configure security as described
in the [CouchDB security and PouchDB authentication](http://www.mircozeiss.com/couchdb-security-and-pouchdb-authentication/) article.

If you would like to test remote replication uncomment the "replication" lines in the source code at the bottom of the `index.html` file.



## Installation

#### Download

Download the project from this git repo.

```bash
git clone git@github.com:kevbaker/pouchdb_todo_example.git
cd pouchdb_todo_example
```
#### Install Webserver

Optionally install node webserver for quick viewing.

```bash
npm install http-server -g
http-server ./
```

#### View in Browser

```
http://localhost:3000/index.html
```

## References

This example was built using the following references. Thanks!

* [Official PouchDB API Refenence](http://pouchdb.com/api.html)
* [Article: CouchDB everywhere with PouchDB - Dale Harvey, Mozilla](https://www.youtube.com/watch?v=TO4oGnDxkY0)
* [Article: Sync multiple AngularJS apps without server via PouchDB](http://www.mircozeiss.com/sync-multiple-angularjs-apps-without-server-via-pouchdb/)
* [CouchDB security and PouchDB authentication](http://www.mircozeiss.com/couchdb-security-and-pouchdb-authentication/)
* [Apache CouchDB Site/Download](http://couchdb.apache.org/)

## Overkill

Sorry for the overkill README. Kind of a bit much for this little example project ;)
