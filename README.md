## cmake-mode mirror

The primary purpose of this mirror is to allow the installation of the
Emacs major mode for cmake, using the straight.el package manager,
*without* needing to clone the full cmake project, just for a single
elisp file.

Install it like so:

```emacs-lisp
(straight-use-package '(cmake-mode :type git
                                   :host github
                                   :repo "northgaard/cmake-mode"
                                   :files (:defaults)))
```
