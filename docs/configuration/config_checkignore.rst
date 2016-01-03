.. _config_checkignore:

===================================
Exclude files/folders from analysis
===================================

To exclude files and/or folders from the analysis, add a **.checkignore** file to the root folder of your master branch.

Files and folders that are mentioned in the **.checkignore** file will be ignored, once your project is re-analyzed.

Follow the following examples, to exclude files and/or folders:

.. code-block:: text

  # Ignore folder content
  test/*
  unittest/*
  my/subfolder/*
  
  # Ignore files
  demo.py
  test/demo.py
  
  # Ingore file in all folders
  **/test.py
  

