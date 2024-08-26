# Rifa's Notes

This is a repository containing most of my personal notes.

It's still early stages. There's no guarantee that this notes setup won't change.

Open to opinions and feedback via the [issue tracker](https://github.com/achrinza/notes/issues).

## How to read

Notes are stored as `.org` files and are authored with Emacs, Org Mode and Org Roam.

No guide on how to setup Emacs to read this yet, but here's the relevant snippet of my `init.el`:

```elisp
(use-package
  org-roam
  :ensure t
  :custom
  (org-roam-directory "/home/user/Documents/git-repos/achrinza/notes")
  :bind (("C-c n l" . org-roam-buffer-toggle)
	 ("C-c n f" . org-roam-node-find)
	 ("C-c n i" . org-roam-node-insert))
  :config (org-roam-setup))
```

## Quality of notes

These are personal notes for my own reference, with some that were transferred from my old stash. Hence, expect varying levels of quality.

A list of transferred legacy notes can be found in "#META Legacy Notes" node.

## Articles vs Notes

After I'm confident with the content quality, I do intend to translate some of these notes into more coherent articles.

The articles won't replace my personal notes as the notes - One is a static story, the other is a living document.

## License

No license yet. But feel free to read and use it as reference.

