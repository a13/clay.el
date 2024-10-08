# Change Log
All notable changes to this project will be documented in this file. This change log follows the conventions of [keepachangelog.com](http://keepachangelog.com/).

## [1.5] - 2024-04-09
- making sure `:base-source-path` is nil in all make calls (since they all use full paths)

## [1.4] - 2024-04-09
- making sure `:base-source-path` is nil when making a single form

## [1.3] - 2024-03-30
- using the CIDER specific `cider-defun-at-point` rather than the Emacs-generic `(thing-at-point 'defun)` - thanks, @genmeblog (#4)
- avoiding specifying format when making a single form - to make the default `[:html]` overridable in user side (e.g., by `[:quarto :html]`) (see #5)

## [1.2] - 2024-01-11
- first official release
- note the API change wrt previous versions- dashes instead of slashes: `clay/make-ns` -> `clay-make-ns`, etc.
