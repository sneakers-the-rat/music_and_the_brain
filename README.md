# MPA 630: Data Science for Public Management

## Theme

This site uses my custom [`ath-tufte-hugo_18-19` theme](https://github.com/andrewheiss/ath-tufte-hugo_18-19) as a submodule.

When cloning for the first time, use this command to get the theme too:

    git clone --recursive https://github.com/andrewheiss/ath-tufte-hugo_18-19.git

To get the theme later, use this command:

    git submodule add \
      https://github.com/andrewheiss/ath-tufte-hugo_18-19.git \
      themes/ath-tufte-hugo_18-19

To update to the latest version of the theme, use:

    git submodule update --recursive --remote

# Additional dependencies

```
brew install pandoc-citeproc
brew install jez/formulae/pandoc-sidenote

install.packages(c("moderndive", "skimr"))
```
