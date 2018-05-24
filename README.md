# markdown-website-builder v0.5
This is a website builder that uses NodeJS and [Markdown-it](https://github.com/markdown-it/markdown-it). It's main feature so far is that you can make multiple HTML pages in one Markdown file.


## How to use:

### Installing:
1. Install NodeJS and NPM
1. Run `npm i` in the file's directory
1. Once NPM is finished installing packages, run `node website-maker.js --init` to make `index.md` with starting syntax
1. Start using markdown!
1. Once you have a page you want, simply run `node website-maker.js` and the program will parse the markdown file into a html file

### Syntax:
All commands are started with `/!` in the format `/!<command>`. Don't include the angle brackets when using commands
- `start page <page>`: Start new page
- `end page <page>`: End page

### Command line flags
- --help, -h: Display help message
- --file, -f: Specify markdown file to read from (default: index.md in current directory)
- --dest, -d: Specify where you want files to be made (default: current directory)
- --tag, -t: Specify command tags (default: /!)
- --init: make a new markdown file with starters
- --mdhelp: Get help for markdown parsing commands

An example of the syntax in use can be found at [examples/index.md](examples/index.md).

Want to contribute? Check out the [Changelog file](CHANGELOG.md)
