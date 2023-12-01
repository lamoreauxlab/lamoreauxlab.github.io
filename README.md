# Lamoreaux Labs Site

Create a new site:
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

Run site locally
```
cd ./path_to_site
bundle exec jekyll serve
```

# References
* https://jekyllrb.com/docs/
* GitHub Pages Create Site https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll
* GitHub Pages test locally https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll