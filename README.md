# company-nginx

Add Nginx directives keywords to company-mode keywords alist.

# Config

``` emacs-lisp
(use-package company-nginx
    :ensure t
    :config
    (eval-after-load 'nginx-mode
      '(add-hook 'nginx-mode-hook #'company-nginx-keywords))
    )
```

