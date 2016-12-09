THDC, Mustang Website 
==========================

## WELCOME!

This is the website for the THDC, Mustang. We're glad you're thinking about contributing to the THDC, Mustang open source project, that's awesome, we <3 you! We love all friendly contributions, and we welcome your ideas about how to make the thdcmustang.gov.np page more user friendly, accessible, elegant, and useful.

This repository is for our public-facing site, which is hosted on thdcmustang.gov.np. If you're unsure about anything, ask us — or submit the issue or pull request anyway. If you’d prefer, you can also reach us by [email](mailto:dev@thdc.gov.np). The worst that can happen is that we’ll politely ask you to change something. 


## Architecture

This is a Jekyll-based website designed to be published via GitHub Pages.

## Installation
This site is made with [Jekyll](http://www.jekyllrb.com). Once you've got
[Ruby](https://www.ruby-lang.org/) on your computer, you can install the
necessary dependencies using the following commands:

```sh
cd cg-landing
gem install bundler
bundle install
```

(Note: depending on how Ruby was installed, you may need to prefix the
last two commands with `sudo`.)

To start up the local server, run:

```sh
bundle exec jekyll serve --baseurl='' -w
```

Then visit [http://localhost:4000](http://localhost:4000) to view it. The `-w`
(or `--watch`) flag tells Jekyll to rebuild the relevant pages when you edit
the source files.

## Contributing

Steps for those *with* commit access:

1. Clone the repository.
2. Create a feature branch.
3. Make your changes in the feature branch.
4. Commit the feature branch.
5. Open a pull request to merge the feature branch into the gh-pages branch.
6. Resolve any conflicts if necessary, then merge your feature branch.

Steps for those *without* commit access:

1. Fork the repository.
2. Make your changes in your fork.
3. Commit the changes to your fork.
4. Open a pull request to merge your fork into the upstream repository.


## Feedback

Give us your feedback! We'd love to hear it. [Open an issue and tell us what you think.](https://github.com/THDCMustang)


## Public domain
By submitting a pull request, you agree to comply with the policies on our [LICENSE](LICENSE.md) page.
