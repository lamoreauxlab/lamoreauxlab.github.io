# Lamoreaux Labs Site

Lastest experiments, tools and services from Lamoreaux Labs.

# Quick Start Guide

```bash
# Clone the project

# Install dependencies
cd ./docs
bundle install

# Run site locally
bundle exec jekyll serve
```

# Maintainance Notes

## Setup 
```bash
mdir new_site
cd new_site

# create a new Jekyll site in the current directory.
jekyll new --skip-bundle .


# Edit GemFile that Jekyll created.
# Comment out gem "jekyll"
# Add gem "github-pages", group: :jekyll_plugins
# Save and close GemFile

# Add webbrick to GemFile
bundle add webrick

# Install the dependencies listed in the Gemfile.
bundle install

# Edit _config.yml
```

## Updating

To update to the latest version of Jekyll and associated dependencies, simply run `bundle update github-pages`.


# References
* https://jekyllrb.com/docs/
* GitHub Pages Create Site https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll
* GitHub Pages test locally https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll
* https://github.com/github/pages-gem