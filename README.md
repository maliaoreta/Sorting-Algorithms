# Sorting-Algorithms
Info about  the following sorting algorithms: Quick, Bubble, Merge, Insertion, and Selection.

## Bubble Sort

### [javascript implementation](public/js/bubble-sort.js)

Bubble Sort is a sorting algorithm that iterates over the collection of data repeatedly, 'bubbling', or sorting lesser values to the beginning. If you imagined your collection of data as bubbles in a cup of soda, the lesser values would be the bubbles that float to the top first, while the heavier bubbles are a little slower to rise to the top. Although the bubbles in your cup of soda won't necessarily be sorted from lightest to heaviest bubbles, it is an example of how the sorting may look when implemented.

Psuedo code for the Bubble Sort algorithm:
```
Create the bubbleSort function that takes in an unsorted Array argument
  Create a boolean variable, swapped, that will let us know if the array is already sorted
  
  While the given array is not sorted,
    
    Create a variable, current, that represents the current value being sorted.
    Create a variable, next, that represents a value for 'current' to be compared against.

    If the current value is greater than the next,
      Swap the current and next values:
        Save the value of 'next' to the index of the 'current' variable
        Save the value of 'current' to the index of the 'next' variable

    If there were no swaps in this iteration, that means the array has already been sorted,
      Set the 'swapped' variable to indicate that we are done and can exit the while loop.

  Return your sorted array!
```

### Best Case
The algorithm's execution time is linearly, O(N), increased with the given Array input.
  e.g. An array that is already sorted

### Worst Case
The algorithm's execution time is exponentially, O(N^2), increased with the given Array input.