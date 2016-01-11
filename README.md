# Atom Ctags Package


This package uses：
[ctags](http://ctags.sourceforge.net),
[autocomplete-plus](https://github.com/saschagehlich/autocomplete-plus)
and fork from [symbols-view](https://github.com/atom/symbols-view)

#Features
* **AutoComplete with ctags**
* **Auto Update the file's tags data when saved**
* go-to-declaration and return-from-declaration
* toggle-file-symbols
* toggle-project-symbols
* "Rebuild Ctags" in context-menu
* "Auto Build Tags When Active" setting, default: false
* 'extraTagFiles' setting, add specified tagFiles.(Make sure you tag file generate with --fields=+KSn)
* 'cmdArgs' setting, add specified ctag command args like: --exclude=lib --exclude=*.js
* 'buildTimeout' setting, specified ctag command execute timeout

![atom-ctags](https://cloud.githubusercontent.com/assets/704762/3483867/e0bac2ee-0397-11e4-89c1-70689f6b8ff3.gif)
