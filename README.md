Suppose you are given (x1, y1), (x2, y2)... (x100, y100) that satisfy the following function: 
<br/>
1. y = (sin(ax + b))^2 <br/> 
2. y = exp(ax + b) <br/>
3. y = 1 / (ax + b) <br/>

except that one among these 100 points does not satisfy the function.

Note that a, b are real constants and are not given to you.

Programming to find out which among these 100 points does not satisfy the function.
It takes two arrays as input (one for x and one for y) and return an index of the point which does not satisfy the function.
