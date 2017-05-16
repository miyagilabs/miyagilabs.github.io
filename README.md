# miyagilabs.github.io

## Setting up GitHub Pages Locally

### Prerequisites

- [Ruby](https://www.ruby-lang.org/en/downloads/) version 2.0 or above, including all development headers.
  - `sudo apt-get install ruby-full`
- [NodeJS](https://nodejs.org/en/download/), or another JavaScript runtime (for CoffeeScript support).
  - `sudo apt-get install nodejs`
- [Bundler](http://bundler.io/) to install and run Jekyll.
  - `sudo gem install bundler`

### Running Locally

After above steps you should be able to run GitHub Pages locally. Install dependencies with the command `bundler install`
in the root of the project directory.<br>
Note: If you get `zlib is missing; necessary for building libxml2` error when running `bundler install` command, you need to install zlib package. In short, you'd execute `sudo apt-get install zlib1g-dev`.

Execute the below command:
```
bundler exec jekyll serve
```
then you will be able to preview your local Jekyll GitHub Pages site in your web browser at http://localhost:4000.
