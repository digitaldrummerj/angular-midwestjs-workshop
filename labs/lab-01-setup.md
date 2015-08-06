# Lab one - Setup and install dependencies

### Prerequisites
* [git](http://git-scm.com/book/en/Getting-Started-Installing-Git)
* [node](http://nodejs.org/download/)
* text-editor

### Ensure all global dependencies have been installed

* [Grunt](https://github.com/cowboy/grunt) `npm install -g grunt-cli`
* [Bower](http://twitter.github.com/bower/) `npm install -g bower`
* [Karma](https://github.com/karma-runner/karma/) `npm install -g karma`
* Nodemon 'npm install -g nodemon'

### Checkout the Github repository

- Create project directory

```
mkdir timesheet-midwestjs-workshop
```

- Checkout project from Github

```
git clone https://github.com/objectpartners/timesheet-midwestjs-workshop.git
```

- You should get output similar to below:

```javascript
Cloning into 'timesheet-midwestjs-workshop'...
remote: Counting objects: 1993, done.
remote: Compressing objects: 100% (18/18), done.
remote: Total 1993 (delta 66), reused 57 (delta 57), pack-reused 1918
Receiving objects: 100% (1993/1993), 306.19 KiB | 0 bytes/s, done.
Resolving deltas: 100% (901/901), done.
Checking connectivity... done.
```

- Change directories to the lab main directory.

```
cd timesheet-midwestjs-workshop
```

- Now let's checkout the `lab-1-setup` branch.

```
git checkout lab-1-setup
```

### Install the application dependencies

- Install the NPM dependencies

```
npm install
```

- Install the Bower dependencies

```
bower install
```
- Compile the `less` and template files.

```
grunt development
```

### Run the application and view the start screen

- In a console window, run:

```
grunt serve:development
```

- This kicks off a Node server and serves up our `index.html` page.

- Open your browser and navigate to http://localhost:3000.

- Verify that you see the welcome page.

![](img/lab01/indexResult.png)

### Commit your changes to Git

```
git add .
git commit -m 'Project started successfully'
```

##### Now let's check out our project's structure so we know what goes where.
