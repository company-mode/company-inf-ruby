[company-mode](http://company-mode.github.io/) completion back-end for `inf-ruby` buffers.

NOTE: Now that `inf-ruby` 2.4.0 supports `completion-at-point`, this backend is deprecated.

You don't need to install anything extra, `company-capf` will work with `inf-ruby`.

Installation
===

Install this from [Marmalade](http://marmalade-repo.org/).

Then, in addition to the usual `company-mode` setup, add this to your init file:

```
(eval-after-load 'company
  '(add-to-list 'company-backends 'company-inf-ruby))
```
