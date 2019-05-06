# Gulp Starter for CSS Tricks Tutorial  

This repo is a gulp starter from this CSS Tricks tutorial.
https://css-tricks.com/gulp-for-beginners/

## Getting Started

### Prerequisites

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.
- A terminal Machine
- Node JS

## Installing

On your terminal machine remember to do run the `sudo npm install` command after cloning this repo to your local.
This will install Gulp and his dependencies.

### Running the tests

Gulp provides us with a `watch` method that checks to see if a file was saved.
- Do `sudo gulp watch` to allow compile CSS and JS files

Browser Sync helps make web development easier by spinning up a web server that helps us do live-reloading easily.
- Do `sudo gulp browserSync` to allow compile CSS and JS files
- Or do `sudo gulp` to allow compile CSS and JS files
- you will see the `index.html` file be loading on `http://localhost:3000/`

### Dist folder
It will uglify CSS and JS files in one. It will copy fonts and compress images.
- Do `sudo gulp build` to allow compile CSS and JS files


### Cleaning up generated DIST files automatically
Since we're generating files automatically, we'll want to make sure that files that are no longer used don't remain anywhere without us knowing. Clean task that clears away from the generated dist folder any image caches that are created, allowing us to remove any old files that were inadvertently kept in dist.
- Do `sudo gulp clean`

## Built With

* [Dropwizard](http://www
  - dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.
