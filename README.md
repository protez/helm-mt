[![MELPA](http://melpa.org/packages/helm-mt-badge.svg)](http://melpa.org/#/helm-mt)

# helm-mt
Helm bindings for managing multi-term terminals

Create and delete multi-term terminals easily with Helm

A call to `helm-mt` will show a list of running terminal sessions
by examining buffers with major mode `term-mode`.  From there, you
should be able to create, delete or switch over to existing
terminal buffers

![helm-mt](mt.gif)

# Setup
Invoke `helm-mt` and bind it to a keyboard shortcut

```
(require 'helm-mt)
(global-set-key (kbd "C-x t") 'helm-mt)
```
