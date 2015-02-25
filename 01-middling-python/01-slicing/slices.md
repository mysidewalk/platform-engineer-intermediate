## Python Slicing

### Preparation
- [Slicing 1](http://stackoverflow.com/questions/509211/explain-pythons-slice-notation/509295#509295)
- [Slicing 2](http://www.diveintopython.net/native_data_types/lists.html#odbchelper.list.slice)

### Related Reading
- [Python Magic Methods](http://www.rafekettler.com/magicmethods.html)

### Exercises
1. Create a class called `StringSlice` that overrides the `__getitem__` method to accept spelled out
    strings for integers 1-9 (e.g. 'one' for 1). Do not worry about negative values.

    - Define a new class
    - Define the `__init__` method to accept and assign a instance based property that you can apply
        the custom slice to
    - Override the `__getitem__` method to use strings
    - Solution can be found in [stringslice-solution.py](stringslice-solution.py)

2. Create a class called `Gradebook` that overrides the `__getitem__` method to accept a slice that
    uses date objects or day values (e.g. 1-365) to return the correct subset.

    - Define a new class
    - Override the `__getitem__` method to use dates or day integers
    - Write your solution in the `slices.py` file where the `Gradebook` class has been defined
    - Solution can be found in [gradebook-solution.py](gradebook-solution.py)

#### Links
Next: [List Comprehensions and Generators](../02-generators/generators.md)