# [SDF04] CodeSpace Cafe Debugging Challenge

### Your Goal
Your task is to debug the CSS at CodeSpace Cafe so that the pastries are neatly in a line.

### The Problem
 The HTML includes a counter and four pastry elements, but they are not properly spaced and overlap each other. 

#### What to Do

1. **Debugging Task:** Review the provided HTML and CSS code. Identify the CSS properties causing the pastries to overlap and adjust them to ensure proper spacing and layout. You should aim to position the pastries in a straight line on the counter, spaced evenly apart.
   
### SOLUTION:
1. Remove position: absolute; in the class pastry.
2. Add display:flex; in the class counter.
3.Add justify-content: space-around; in the class counter.

