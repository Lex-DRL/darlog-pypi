# [darlog-pypi](https://pypi.org/project/darlog-pypi/)

[Lex Darlog](https://github.com/Lex-DRL)'s tiny tools library preventing human errors when publishing packages to pypi.org

Main feature is `ReadmeUpdater` class, which does a few handy tricks with the GitHub's `ReadMe.md` <-> PyPI's "long description", changing them dynamically at build time:
- ensure the main title reflects the actual project name (defined in the main package itself) - in case you've copied it from another template repo and forgot to change it;
- makes the title itself a link which cross-references from PyPI to GitHub and vice versa.
