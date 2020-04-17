
OpenCV Document Scanner
=======================

A simple mobile document scanner using OpenCV.
It involves just three stpes to create a document scanner.


**Step 1:**

Identify the edges from the image

**Step 2:**

Use the edges in the image to find the contour (outline) representing the piece of paper being scanned.

**Step 3:**

Apply a perspective transform to obtain the top-down view of the document.


Usage
~~~~~

.. code-block:: bash

	python scanner.py --image <path/to/image/file>

