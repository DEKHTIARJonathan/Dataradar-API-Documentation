API Documentation
================================

Now that we have our basic skeleton,
let's document the project.
As you might have guessed from the name,
we'll be documenting a basic web crawler.

For this project,
we'll have the following pages:

* Index Page
* Support
* Installation
* Cookbook
* Command Line Options
* API

Let's go over the concepts we'll cover,
and then we can talk more about the pages to create.

GET articles/all
****************

A lot of these RST syntax examples are covered in the Sphinx :ref:`sphinx:rst-primer`.

.. index::
   pair: Syntax; Hyperlink

GET article/id
**************

A lot of these RST syntax examples are covered in the Sphinx :ref:`sphinx:rst-primer`.

.. index::
   pair: Syntax; Hyperlink

.. code-block:: json

	{
		"menu": {
			"id": "file",
			"value": "File",
			"popup": {
				"menuitem": [
					{"value": "New", "onclick": "CreateNewDoc()"},
					{"value": "Open", "onclick": "OpenDoc()"},
					{"value": "Close", "onclick": "CloseDoc()"}
				]
			}
		}
	}

GET articles/list
*****************

A lot of these RST syntax examples are covered in the Sphinx :ref:`sphinx:rst-primer`.

.. index::
   pair: Syntax; Hyperlink
   

GET article/search
******************

A lot of these RST syntax examples are covered in the Sphinx :ref:`sphinx:rst-primer`.

.. index::
   pair: Syntax; Hyperlink

.. code-block:: json

	{
		"menu": {
			"id": "file",
			"value": "File",
			"popup": {
				"menuitem": [
					{"value": "New", "onclick": "CreateNewDoc()"},
					{"value": "Open", "onclick": "OpenDoc()"},
					{"value": "Close", "onclick": "CloseDoc()"}
				]
			}
		}
	}