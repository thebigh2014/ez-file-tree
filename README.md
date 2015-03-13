Angular File Tree Directive
===========================

##Installation

```bash
$ bower install ez-file-tree
```

##Demo

See a demo of index.html at http://rawgit.com/jdewit/ez-file-tree/master/index.html

##Configure

Some things such as the icon classes are configurable, just override the EzFileTreeConfig constant.

##About

This directive is a bit more than just a recursive tree. It also sets some private 
fields on each item depending on a particular action.

- _selected => True if the file/folder is selected
- _active => True if any children files are checked


