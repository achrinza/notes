<!-- -*- coding: utf-8 -*-
SPDX-License-Identifier: CC-BY-SA-4.0
SPDX-FileCopyrightText: Copyright (C) 2024 Rifa Ilyasa Achrinza -->

# Rifa's Notes

This is a repository containing most of my personal notes.

It's still early stages. There's no guarantee that this notes setup won't change.

Open to opinions and feedback via the [issue tracker](https://github.com/achrinza/notes/issues).

## How to read

Notes are stored as `.org` files and are authored with Emacs, Org Mode and Org Roam.

No guide on how to setup Emacs to read this yet, but here's the relevant snippet of my `init.el`:

<!--
SPDX-SnippetBegin
SPDX-License-Identifier: AGPL-3.0-only
SPDX-SnippetCopyrightText: Copyright (C) 2024 Rifa Ilyasa Achrinza
SPDX-SnippetAttributionText: <text>
This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published by
the Free Software Foundation, version 3 of the License.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.
You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
</text> -->
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
<!-- SPDX-SnippetEnd -->

## Quality of notes

These are personal notes for my own reference, with some that were transferred from my old stash. Hence, expect varying levels of quality.

A list of transferred legacy notes can be found in "#META Legacy Notes" node.

### Articles vs Notes

After I'm confident with the content quality, I do intend to translate some of these notes into more coherent articles.

The articles won't replace my personal notes as the notes - One is a static story, the other is a living document.

## License

Documentation is licensed under CC-BY-SA-4.0.

Code snippets are licensed under AGPL-3.0-only.
