# Knowage-Documentation

## Structure
                                                   
Titles are underlined with a nonalphanumeric character at least as long as the text.
* `#` for parts
* `=` for chapters
* `-` for sections
* `~` for subsections
* `^` for paragraphs

### Example

```
Part I
########

Chapter 2
===========

Section 3
-----------
```

## Code

To adding a code you need to use this syntax:

.. code-block:: Type of language
    :linenos:
    :caption: Title.
      Text of the code

### Example

```
.. code-block:: xml
    :linenos:
    :caption: Pointing at a numerical column.
    
      <COLUMNS> 
        <COLUMN field="store_id" visible="false" editable="false" /> 

```

## Image

There are two different way to add an image, its depend if it is inline of the text or is out of the text.

1. Added an image inline:

  Insert the |imageX| inside the text and then recall it outside the text (anywhere in the text) whit this syntax:
  
  .. |imageX| image:: media/imageX.png
                   :width: dimension
                   
2. Added an image oustide:

  At the poin you need to insert an image use this:
  
  .. figure:: media/imageX.png

    Caption of the image.

### Example

```
1.
If your dataset is similar to another existing dataset, you can click the **Clone** icon |image16|.

.. |image16| image:: media/image23.png
   :width: 30
   
2.

In the **Detail** tab you define the Name, the Label and an optional Description of the dataset (refer to figure below). 

.. _datasetpanel:
.. figure:: media/image22.png

    Dataset Panel.

```


