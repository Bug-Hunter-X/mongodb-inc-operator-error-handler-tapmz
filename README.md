# MongoDB $inc operator type error
This code demonstrates an error that arises when using the `$inc` operator in MongoDB update operations. The error occurs due to providing a string value instead of a number to the `$inc` operator, which is designed to increment numerical values. 

The `bug.js` file showcases the erroneous code.  The `bugSolution.js` file contains the corrected version.  This example highlights the importance of carefully checking the data types when interacting with MongoDB operators.