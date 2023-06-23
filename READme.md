# Make Python Code Faster

### ***Don’t Run Loops in Python, Instead, Use These!***

## ***1. Filter***
    > It filters iterable objects for us. We are going to pass the filtering conditions in form of a function and this function is going to use to filter each element in the iterable object.

    >   Syntax:
        > filter(function, iterable)

## ***2. MAP***
    > This function is really useful if you want to apply a function to each value of an iterable object like a list, tuple, or even a pandas series.

    > Syntax:
        > map(function, iterable)

## ***3. Reduce***
    > Python offers a function called reduce() that allows you to reduce a list in a more concise way. this function performs functional computation by taking a function and iterable like a list, tuple, series, etc as arguments and returns a single value as output.

    > Syntax:
        > reduce(function, iterable)

    > The reduce() function applies the function of two arguments cumulatively to the items of the list, from left to right to reduce the list into a single value.
    > Unlike the map() and filter() functions, the reduce() is not a built-in function in Python. The reduce() function belongs to the functools module.
    > Steps of how to reduce function work in python
        - The function passed as an argument is applied to the first two elements of the iterable.
> After this, the function is applied to the previously generated result and the next element in the iterable.
        - This process continues until all of the iterable items are iterated.
        - A single value is returned as a result of applying the reduce function on the iterable.
    > Let’s understand the steps with an illustration:
        - If we have a list of numbers [1,2,3,4,5] that is reduced by applying the addition function.
        - As a final output will be the sum of all the numbers of the list 15.

