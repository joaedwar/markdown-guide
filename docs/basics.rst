================
Markdown Basics
================

This should cover 99% of your Markdown needs.

Headers
========

HTML headings are produced by placing a number of hashes before the header
text corresponding to the level of heading desired (HTML offers six levels of
headings), like so::

    # First-level heading

    #### Fourth-level heading

This will render out into the following HTML tags:

.. code-block:: html

    <h1>First-level heading</h1>
    
    <h4>Fourth-level heading</h4>

Paragraphs
===========

A paragraph is one or more consecutive lines of text separated by one or more
blank lines. Normal paragraphs should not be indented with spaces or tabs::

    This is a paragraph. It has two sentences.

    This is another paragraph. It also has two sentences.

This will render out into the following HTML tags:

.. code-block:: html

    <p>This is a paragraph. It has two sentences.</p>
    
    <p>This is another paragraph. It also has two sentences.</p>    