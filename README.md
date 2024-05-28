# Website of the CODEML Workshop

This repository contains the source files for [codeml-workshop.github.io/codeml2024](https://codeml-workshop.github.io/codeml2024), the website of the **CODEML** 2024 workshop.

<br>
<div align="center">
    <img align="center" src="assets/img/logos/logo-codeml.svg" alt="logo" width="600" style="padding-right: 10px; padding left: 10px;" title="CODEML"/>
</div>
<br>

## Requesting Changes

You can request features or report bugs by creating an [issue](https://github.com/codeml-workshop/codeml.github.io/issues). Be aware that your requested change has a much higher probability of being considered if you suggest it directly via a pull request (see contribution guide below).

## Contributing

The site is built using [Jekyll](https://jekyllrb.com/) with the [al-folio theme](https://github.com/alshedivat/al-folio). Bibliography support is provided by [Jekyll-Scholar](https://github.com/inukshuk/jekyll-scholar).

### Simple Changes

You can make simple changes directly in the browser. 

1. Fork the repository on Github. (Optional for Github organization members.)
2. Navigate to the file you want to change on GitHub and click the "Edit this file" button. Make changes and create a commit.
3. Make a pull request to the main repository with your changes. (Optional for Github organization members.)


### Advanced

#### Forking and Cloning the Repository
Fork the repository and GitHub and clone it to your local machine using `git`. It is recommended to set up `codeml-workshop/codeml.github.io` as a second `upstream` remote so you can easily keep up-to-date with the main repository. More detail [here](https://git-scm.com/book/en/v2/Git-Basics-Working-with-Remotes).

#### Setting Up Ruby

Install Ruby and Bundler via the following instructions depending on your platform:

**Linux:** 

```bash
sudo apt-get install ruby-dev
sudo gem install bundler
```

**Mac:**
Installs [`rbenv`](https://github.com/rbenv/rbenv) to manage your Ruby version and Ruby itself. See the [`rbenv` documentation](https://github.com/rbenv/rbenv#how-it-works) for more instructions on how it works.

```bash
brew install rbenv ruby-build
rbenv init # Follow the printed instructions to setup rbenv in your shell.
rbenv global 3.1.2 # Sets your default version of ruby globally.
```

Now restart your shell and navigate to the directory of this repository.

#### Installing Dependencies

```bash
gem install bundler
```

Then install the required dependencies and plugins for the site via:

```bash
bundle install
```

#### Making and Viewing Changes

You can edit the website and view the changes in real-time via:

```bash
bundle exec jekyll serve --livereload --open-url
```


#### Creating a Pull Request
Once you are satisfied with your changes, `git push` them to your fork on GitHub and create a pull request to the main repository.
