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

I tested this plugin against `garbas's Snipmate fork`_.
If it doesn't work with your own configuration, please let me know.

.. _garbas's Snipmate fork: https://github.com/garbas/vim-snipmate

Dependencies
------------
* Vim (of course)
* Snipmate_.

Installation
------------
This addon is compatible with Pathogen_ and Vundle_.
If you use one of them,
you are awesome so you'll know what to do.

I pretend to support installation with VAM_ as well,
but I haven't tried it.

If you are an old-fashioned Vimmer,
just drop the bib.snippets_ file
into the ``snippets`` directory
of your Snipmate install.

.. _Snipmate: https://github.com/garbas/vim-snipmate
.. _Pathogen: https://github.com/tpope/vim-pathogen
.. _VAM: https://github.com/MarcWeber/vim-addon-manager
.. _bib.snippets: https://github.com/rbonvall/snipmate-snippets-bib/blob/master/snippets/bib.snippets

Author
------
Roberto Bonvallet <rbonvall@gmail.com>

