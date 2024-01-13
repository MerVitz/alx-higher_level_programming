# Python - Inheritance

In this project, I learned about Python class inheritance. I learned about the differences between super- and sub-classes while practicing inheritance, defining classes with multiple base classes, and overriding inherited methods and attributes.

## Tests :heavy_check_mark:

* [tests](./tests): Folder of test files:
    * [1-my_list.txt](./1-my_list.txt)
    * [7-base_geometry.txt](./7-base_geometry.txt)

## Function Prototypes :floppy_disk:

Prototypes for functions written in this project:

| File                    | Prototype                             |
| ----------------------- | ------------------------------------- |
| `0-lookup.py`           | `def lookup(obj):`                    |
| `2-is_same_class.py`    | `def is_same_class(obj, a_class):`    |
| `3-is_kind_of_class.py` | `def is_kind_of_class(obj, a_class):` |
| `4-inherits_from.py`    | `def inherits_from(obj, a_class):`    |
| `101-add_attribute.py`  | `def add_attribute(obj, att, value):` |

## Tasks :page_with_curl:

* **0. Lookup**
  * [0-lookup.py](./0-lookup.py): Python function that returns a list of available attributes and methods of an object.

* **1. My list**
  * [1-my_list.py](./1-my_list.py): Python class `MyList` that inherits from `list`. Includes:
    * Public instance method `def print_sorted(self):` that prints the list in ascending sorted order (assumes all list elements are `int`s).

* **2. Exact same object**
  * [2-is_same_class.py](./2-is_same_class.py): Python function that returns `True` if an object is exactly an instance of a specified class; otherwise `False`.

* **3. Same class or inherit from**
  * [3-is_kind_of_class.py](./3-is_kind_of_class.py): Python function that returns `True` if an object is an instance or inherited instance of a specified class; otherwise `False`.

* **4. Only sub class of**
  * [4-inherits_from.py](./4-inherits_from.py): Python function that returns `True` if an object is an inherited instance (either directly or indirectly) from a specified class; otherwise `False`.

* **5. Geometry module**
  * [5-base_geometry.py](./5-base_geometry.py): An empty Python class `BaseGeometry`.

* **6. Improve Geometry**
  * [6-base_geometry.py](./6-base_geometry.py): Python class `BaseGeometry`. Builds on [5-base_geometry.py](./5-base_geometry.py) with:
    * Public instance method `def area(self):` that raises an `Exception` with the message `area() is not implemented`.

* **7. Integer validator**
  * [7-base_geometry.py](./7-base_geometry.py): Python class `BaseGeometry`. Builds on [6-base_geometry.py](./6-base_geometry.py) with:
    * Public instance method `def integer_validator(self, name, value):` that validates the parameter `value`.
    * Assumes the parameter `name` is always a string.
    * The parameter `value` must be an `int`, otherwise, a `TypeError` exception is raised with the message `<name> must be an integer`.
    * The parameter `value` must be greater than `0`, otherwise, a `ValueError` exception is raised with the message `<value> must be greater than 0`.

* **8. Rectangle**
  * [8-rectangle.py](./8-rectangle.py): Python class `Rectangle` that inherits from `BaseGeometry` ([7-base_geometry.py](./7-base_geometry.py)). Includes:
    * Private attributes `width` and `height` - validated with
integer_validator.
* Instantiation with width and height: def __init__(self, width, height):


##Author: Amakalu Vitalis
##Email: amakaluvitalis202@gmail.com
