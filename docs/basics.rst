================
Markdown Basics
================

This should cover 99% of your Markdown needs.
    
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

Line Return
============

To force a line return, place two empty spaces at the end of a line.

Markdown::

    Forcing a line-break\s\s
    Next line in the list

Output:

.. code-block:: html

    Forcing a line-break<br>
    Next line in the list

Links: Inline
===============

Inline-style links use parentheses immediately after the link text.

Markdown::

    This is an [example link](http://example.com/).

Output:

.. code-block:: html

    <p>This is an <a href="http://example.com/">example link</a>.</p>
    
Links: Inline with title
========================

Markdown::

    This is an [example link](http://example.com/ "With a Title").

Output:
    
.. code-block:: html

    <p>This is an <a href="http://example.com/" 
        title="With a Title">example link</a>.</p>
    
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


Links: Reference
================

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