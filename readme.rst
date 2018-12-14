Currently this fork is (in functionality and usage) equal to the one in CTAN.

At the moment, usage information is just at `tex.stackexchange.com <https://tex.stackexchange.com/a/463842/98850>`_.

Arguments
---------

* ``-h`` ``--help`` Print help text and exit.
* ``-c`` ``--compiler`` Change LaTeX compiler, defaults to pdflatex.
* ``-a`` ``--arguments`` Arguments to pass to compiler, default is ``-synctex=1 -interaction=nonstopmode``
* ``--texlive_bin`` Custom location for the TeX Live bin folder.
* ``--terminal_only`` Forces us to assume we can run only in this terminal.  Permission escalators will appear here rather than graphically or in a new terminal.
* ``-s`` ``--speech_when`` Toggles speech-synthesized notifications (where supported).  OPTION can be "always", "never", "installing", "failed", or some combination.
* ``-f`` ``--fail_silently`` If tlmgr cannot be found, compile document anyway.
