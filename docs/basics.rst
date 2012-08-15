================
Markdown Basics
================

This should cover 99% of your Markdown needs.

Headers
========

HTML headings are produced by placing a number of hashes before the header
text corresponding to the level of heading desired (HTML offers six levels of
headings).

Markdown::

    # First-level heading

    #### Fourth-level heading

Output:

.. code-block:: html

    <h1>First-level heading</h1>
    
    <h4>Fourth-level heading</h4>

Paragraphs
===========

A paragraph is one or more consecutive lines of text separated by one or more
blank lines. Normal paragraphs should not be indented with spaces or tabs.

Markdown::

    This is a paragraph. It has two sentences.

    This is another paragraph. It also has two sentences.

Output:

.. code-block:: html

    <p>This is a paragraph. It has two sentences.</p>
    
    <p>This is another paragraph. It also has two sentences.</p>    
    
Blockquotes
============

To enclose a segment of text in blockquotes, one must prefix each written line
with a less-than sign.

Markdown::

    > ## Blockquoted header
    >
    > This is blockquoted text.
    >
    > This is a second paragraph within the blockquoted text.
    
Output:

.. code-block:: html

    <blockquote>
        <h2>Blockquoted header</h2>
    
        <p>This is blockquoted text.</p>

        <p>This is a second paragraph within the blockquoted text.</p>

    </blockquote>


Links
============

TODO

Line Return
============

TODO

Italics
========

TODO

Strong
========

TODO

Lists
========

TODO

Code
=====

TODO

Horizontal rules
=================

TODO