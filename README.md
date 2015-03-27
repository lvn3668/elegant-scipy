Planning
=======
Just some notes to help us plan

Deadlines
========
Feb: 2 chs: 2/15/15
May: half chs: 5/1/15
Sep: First full draft: 9/15/15
Oct: All in:  10/15/15

Availabilities
-------------
Stéfan: I am moving to the US this coming month, so I don't think I'll be able to write much before February.  I am out of action half of May, the whole of June, and part of July, so that may slow me down for the first full draft. 

Harriet: I'll be pretty busy in late July and August.

Juan: Most of August is out

Chapters/Ideas
==============
Based on: https://github.com/jni/my-documents/blob/oreilly-book-proposal/oreilly.markdown

*Preface/Introduction:* 

Why SciPy?

Who is this book for?

Ecosystem and community.

Conventions (e.g. NumPy docstring
conventions). Not sure if this fits here?

Definitions: What are SciPy NumPy matplotlib and pandas (or save some of these for when the are introduced?)

Getting Started:

Installation - Anaconda
Using IPythonNotebook and accessing the book materials

*hdashnow: Maybe a chapter before Image segmentation that with some easy analysis (e.g. data exploration, some graphing?) to get reader familiar with Numpy Basics and similar before introducing more domain-specific code*

**Chapter 1:** Image segmentation using `ndimage.generic_filter`. This includes
an introduction to the NumPy array, memory layout, strides, F- and
C-contiguity, 1D, 2D, and nD filters, and finally filtering to produce a graph
and segmentation from that graph. (This may be broken down into several
smaller chapters.)

**Chapter 2:** Fourier Transforms. (Need to find a killer application/use for
this one, but it's a central enough topic that it will be a high priority to
include such an example.)

**Chapter 3:** Use of sparse matrices to evaluate clustering accuracy.

**Chapter 4:** Eigendecomposition. (Same as FTs.)

**Chapter 5:** Optimization. (idem)

**Chapter 6:** Streaming data. (idem, but specifically want to include use of
Matt Rocklin's Toolz)

**Chapter 7:** Basic statistics. 
*hdashnow: I wonder if this would work better as a first chapter to introduce some basic concepts?*

**Chapter -1:** Contributing to the SciPy ecosystem: how to use git and github,
and follow best practices, to contribute to SciPy and related packages.

*hdashnow: Split up this material? Introduce some of the ideas in the preface/introduction but save the more advanced stuff for a later chapter. That way the reader has a chance to get their head around SciPy before we talk them into contributing to the community.*

... Perhaps additional chapters with awesome examples using scikit-learn,
scikit-image, pandas, astropy, etc. The exact contents will be determined by
code submissions, which will be triaged to canvas as wide a footprint of SciPy
as possible.
