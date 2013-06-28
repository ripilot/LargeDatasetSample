LargeDatasetSample
==================

This is a sample application that uses Core Data and NSFetchedResultsController to display dataset of 50 000 items. It is similar to Contacts of the Phone application.

[![](http://lukagabric.com/wp-content/uploads/2013/06/LargeDatasetSample.png)](http://lukagabric.com/wp-content/uploads/2013/06/LargeDatasetSample.png)

LAbstractSearchViewController
-----------------------------

LAbstractSearchViewController is intended to be subclassed to override getters and adjust the data to be displayed. Check the MainViewController class for more details.

MainViewController
------------------

MainViewController extends the LAbstractSearchViewController class in order to override protected getters and display managed objects.

DataController
--------------

Autogenerated Core Data methods are moved out of AppDelegate into DataController singleton.
