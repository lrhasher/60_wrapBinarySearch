# 60_wrapBinarySearch

Is the lowLim greater than the highLim? // boolean deciding which sol to use
  If yes, return -2.                    // solution to base case
If no,
  if findMe is the middle page of the array, 
    return the page number.             // solution to other base case
  // recursive cases
  if findMe is before the middle page of the array,
    return 
      the result of applying these instructions to the first half of the array.    
  if findMe is after the middle page of the array,
    return
      the result of applying these instructions to the second half of the array.
