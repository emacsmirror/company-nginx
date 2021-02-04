# company-nginx

Add Nginx directives keywords to company-mode keywords alist.

# Config

``` emacs-lisp
(use-package company-nginx
  :ensure t
  :config (add-hook 'nginx-mode-hook (lambda () (add-to-list 'company-backends #'company-nginx))))
```
