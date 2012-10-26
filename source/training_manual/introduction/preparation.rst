|LS| Adding your first layer
============================

We will start the application, and create a basic map to use for examples and
exercises.

**The goal for this lesson:** To get started with an example map.

.. note::  Before starting this exercise, QGIS must be installed on your
   computer.

Launch QGIS from its desktop shortcut, menu item, etc., depending on how you
configured its installation.

.. note::  The screenshots for this course were taken in QGIS 1.8 running on
   Ubuntu 11.10 and Windows XP. Depending on your setup, the screens you
   encounter may well appear somewhat different. However, all the same buttons
   will still be available, and the instructions will work on any OS. You will
   need QGIS 1.8 (the latest version at time of writing) to use this course.

Let's get started right away!

.. _backlink-interface-preparation-1:

|basic| |FA| Prepare a map
--------------------------

* Open QGIS. You will have a new, blank map.

* Look for the |mActionAddNonDbLayer| :sup:`Add Vector Layer` button:
* Click on it to open the following dialog:

.. figure:: /static/training_manual/interface/003.png
   :align: center

* Click on the **[Browse]** button and navigate to the file
  :file:`exercise_data/streets.shp` (in your course directory). With this file
  selected, click **[Open]**. You will see the original dialog, but with
  the file path filled in. Click **[Open]** here as well. The data you
  specified will now load.

Congratulations! You now have a basic map. Now would be a good time to save
your work.

* Click on the |mActionFileSaveAs| :sup:`Save As` button:
* Save the map under :file:`exercise_data/` and call it :file:`basic_map.qgs`.

:ref:`Check your results <interface-preparation-1>`

|IC|
----

You've learned how to add a layer and create a basic map!

|WN|
----

Now you're familiar with the function of the |mActionAddNonDbLayer|
:sup:`Add Vector Layer` button, but what about all the others? How does this
interface work? Before we go on with the more involved stuff, let's first take
a good look at the general layout of the QGIS interface. This is the topic of
the next lesson.
