THDC, Mustang Website 
=======

This repository is for our public-facing site, which will be hosted on thdcmustang.gov.np. We're so glad you're thinking about contributing to the THDC, Mustang's open source project, that's awesome, we <3 you! We love all friendly contributions, and we welcome your ideas about how to make the thdcmustang.gov.np page more user friendly, accessible, elegant, and useful.

If you are unsure about anything, ask us — or submit the issue or pull request anyway. If you’d prefer, you can also reach us by [email](mailto:thdcmustang@gmail.com). The worst that can happen is that we’ll politely ask you to change something. 


## Architecture

This site is made with [Jekyll](http://jekyllrb.com), an open source static site generator and designed to 
be published via GitHub pages.

## Installation
You can take all the files of this site and run them just on your computer 
as if it were live online, only it is just on your machine though. Once you have got
[Ruby](https://www.ruby-lang.org/) on your computer, you can install the
necessary dependencies using the following commands:

```sh
cd thdcmustang.github.io
gem install bundler
bundle install
```

(Note: depending on how Ruby was installed, you may need to prefix the
last two commands with `sudo`.)

To start up the local server, run:

```sh
bundle exec jekyll serve --baseurl='' -w
```

Then visit [http://localhost:4000](http://localhost:4000) on your browser to 
view it. The `-w`(or `--watch`) flag tells Jekyll to rebuild the relevant 
pages when you edit the source files.

## Contributing

1. Fork the repository (or clone it if you have commit access)
2. Create a feature branch
3. Make your changes in the feature branch
4. Commit the feature branch
5. Push the feature branch to GitHub
6. Open a pull request to merge the feature branch

Feel free to ping [@MegaMind98](https://github.com/MegaMind98) with any questions you
may have.

## Feedback

Give us your feedback! We would love to hear it. [Open an issue and tell us what you think.](https://github.com/THDCMustang/thdcmustang.github.io/issues)
