emacs-pdb
=========

pdb-mode is an emacs-lisp minor mode for Emacs to perform a number of useful editing functions on Protein DataBank (PDB) formatted files. XEmacs and/or GNU Emacs are available for most computing platforms.

## emacs-pdb-mode & rna-pdb-tools

rna-pdb-tools can be used side-by-side https://github.com/mmagnus/emacs-pdb-mode to edit files structural files in the PDB format.

http://rna-pdb-tools.readthedocs.io/en/latest/emacs.html

## How to customize the colors?
You can play around with:

    (make-face 'pdb-key1-face)
    (set-face-background 'pdb-key1-face "dim gray")
    (make-face 'pdb-comment-face)
    (set-face-foreground 'pdb-comment-face "dark gray")

.. a full list of Emacs color you can get by typing `M-x list-colors-display`.

Select a residue:

![screenshot](doc/screenshota.png)

.. change Chain ID:

![screenshot](doc/screenshotc.png)

Send a part of the PDB file directly to PyMOL:

![screenshot](doc/screenshotb.png)
