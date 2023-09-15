# Emacs mode for [aiken](https://github.com/aiken-lang/aiken)

An emacs major mode providing syntax highlighting, indentation and formatting
commands for the Aiken smart contract language.

## Installation

The package is not yet on MELPA, so pointing your emacs config to this
repository is the way to go for now.

### [doom-emacs](https://github.com/doomemacs/doomemacs/) (recommended :smiling_imp:)

Add this to your `packages.el`:

```elisp
(package! aiken-mode
  :recipe (:host github :repo "aiken-lang/aiken-mode"))
```

Or for faster feedback time during development:

```elisp
(package! aiken-mode
  :recipe (:local-repo "~/code/aiken-mode"))
```

And run `doom sync`.

### use-package

```elisp
(use-package aiken-mode
  :load-path "~/path/to/aiken-mode")
```

### vanilla

```elisp
(add-to-list 'load-path "~/path/to/aiken-mode")
(load-library "aiken-mode")
```
