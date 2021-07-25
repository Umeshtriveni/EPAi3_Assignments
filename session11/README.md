<h1 align="center">Iterator and iterable </h1>

<h2 align="center"> Assignment Question </h2>


### Project: Description

* The starting point for this project is the Polygon class and the Polygons sequence type we created in the previous project.

The code for these classes along with the unit tests for the Polygon class are below if you want to use those as your starting point. But use whatever you came up with in the last project.
* We have two goals:



### Goal 1

* Refactor the Polygon class so that all the calculated properties are lazy properties, i.e. they should still be calculated properties, but they should not have to get recalculated more than once (since we made our Polygon class "immutable").

### Goal 2
* Refactor the Polygons (sequence) type, into an iterable. Make sure also that the elements in the iterator are computed lazily - i.e. you can no longer use a list as an underlying storage mechanism for your polygons.

You'll need to implement both an iterable, and an iterator.


## Test Cases

Test cases have been developed in the notebook to check the `Goal 1` and `Goal 2`. There are two sections in the notebook, first section tests `objective 1` over `properties`, `__repr__`,`__eq__` & `__gt__` function. The second section contains the test cases for `objective 2` over `properties`,`__repr__`, `__len__` & `__getitem__`.

