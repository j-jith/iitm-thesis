iitm-thesis
===========

This is a LaTeX class for preparing PhD, MS, M.Tech and B.Tech thesis according
to the IIT Madras guidelines. The original class, which can be found `here
<https://mat.iitm.ac.in/usefullink.html>`_, was last updated in March
2005 and passes some obsolete options to certain packages. In addition, it does
not adhere to certain guidelines like "chapters should start on odd-numbered
pages". This version of the class aims to fix these issues. In order to do so,
the following changes have been made to the original class:

- Removed the obsolete ``compat2`` option from the ``geometry`` package.

- Added ``emptypage`` package to disable page numbering in blank pages.

- Added ``twoside`` option to ``article`` (synopsis) and ``report`` (thesis)
  classes for left-margin adjustment during two-sided printing. Also, you can
  now use ``\cleardoublepage`` to start a new page on the right hand side.

- Added ``openright`` option to ``report`` (thesis) class to ensure chapters
  start on the right hand side (odd page numbers)

- Added ``\pagenumbering{gobble}`` to "Title", "Quotation", "Dedication", and
  "Thesis Certificate" pages to ensure they start on the right hand side (odd
  page numbers)

- Roman page numbering now starts from the "Acknowledgements" page.

This class was tested on TeX Live 2016. Please do not use an older
distribution.

Files included
--------------

- ``iitmdiss.cls`` - main class file

- ``iitm.bst`` - bibliography style

- ``atbeginend.sty`` - for removing space around and within environments
  [#squeeze]_

- ``iitm.pdf`` - IIT Madras logo

- ``synposis.tex`` - sample synopsis

- ``thesis.tex`` - sample thesis

- ``refs.bib`` - sample bibliography file


LaTeX packages required
-----------------------

- `geometry <https://www.ctan.org/pkg/geometry>`_

- `setspace <https://www.ctan.org/pkg/setspace>`_

- `caption <https://www.ctan.org/pkg/caption>`_

- `natbib <https://www.ctan.org/pkg/natbib>`_

- `emptypage <https://www.ctan.org/pkg/emptypage>`_

For compiling the sample synopsis and thesis
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- `hyperref <https://www.ctan.org/pkg/hyperref>`_

- `amsmath <https://www.ctan.org/pkg/amsmath>`_

- `graphicx <https://www.ctan.org/pkg/graphicx>`_


The original LaTeX class
------------------------

The original LaTeX class, created by Prabhu Ramachandran, can be found
`here <https://mat.iitm.ac.in/usefullink.html>`_.


Footnotes
---------

.. [#squeeze] `Squeezing Space in LaTeX <http://www-h.eng.cam.ac.uk/help/tpl/textprocessing/squeeze.html>`_

