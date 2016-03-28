# Getting started with Semantic UI development

Semantic is a development framework that helps create beautiful, responsive layouts using human-friendly HTML. Very similar to Bootstrap, but better!

This repository holds the sources and the artifacts (the compiled results) of the custom theme we created for Semantic UI. The reason we track the built files in version control (against common best practices) is to eliminate the need for every developer to compile the styles on their own, install the many dependencies, while usually the theme is not changed much by most developers.

Semantic-UI Homepage: http://semantic-ui.com/
Read about the build tools here: http://semantic-ui.com/introduction/build-tools.html


# Semantic-UI customization instructions

* put variables that configure existing css in '\*.variables' files
* if no other way, put css styles that overrides themes in '\*.overrides' files
* Make sure to run build or watch to see results

```
npm run build
or
npm run watch
```

* To add new customizations, look at an example /site folder in the website. it has many many empty files. We removed them and left only the ones we actually use. Bring back new ones you need to edit

* see http://semantic-ui.com/usage/theming.html
* see http://learnsemantic.com/
