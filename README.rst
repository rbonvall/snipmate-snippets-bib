Snipmate.vim support for BibTeX files
=====================================

This plugin provides some snippets
for writing BibTeX (``.bib``) files.

The supported entry types are:
``Article``,
``Book``,
``Booklet``,
``Conference``,
``InBook``,
``InCollection``,
``InProceedings``,
``Manual``,
``MastersThesis``,
``Misc``,
``PhDThesis``,
``Proceedings``,
``TechReport`` and
``Unpublished``.
The trigger words are these names converted to lower case.
Most of the optional fields (such as ``annote`` and ``eprint``) are not included.

I tested this plugin against `garbas's Snipmate fork`_ and using Pathogen.
If it doesn't work with your own configuration, please let me know.

.. _garbas's Snipmate fork: https://github.com/garbas/vim-snipmate

Dependencies
------------
* Vim (of course)
* Snipmate_.

Installation
------------
If you use Pathogen_,
just clone this repository
into your ``bundle`` directory::

    cd ~/.vim/bundle
    git clone git://github.com/rbonvall/snipmate-snippets-bib.git

Personally,
I prefer to add bundles as submodules
of the git repository for my ``.vim`` directory (`rbonvall/dotvim`_)::

    cd ~/.vim
    git submodule add git://github.com/rbonvall/snipmate-snippets-bib.git bundle/snippets-bib
    git submodule init
    git submodule update
    git commit  -m 'Add bib snippets to bundles as submodule'

If you don't use Pathogen
(you should!)
just drop the bib.snippets_ file
into the ``snippets`` directory
of your Snipmate installation.

.. _Snipmate: https://github.com/garbas/vim-snipmate
.. _Pathogen: https://github.com/tpope/vim-pathogen
.. _rbonvall/dotvim: https://github.com/rbonvall/dotvim
.. _bib.snippets: https://github.com/rbonvall/snipmate-snippets-bib/blob/master/snippets/bib.snippets

Author
------
Roberto Bonvallet <rbonvall@gmail.com>

