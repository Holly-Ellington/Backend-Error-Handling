# Backend-Error-Handling

Instructions
Your goal for this lesson is to get the tests to pass. To do so, you will be building two functions to handle errors:

A catch-all middleware function that is called whenever a nonexisting route is called. The response should be as follows:

An error occurred: Could not find route.
An error-handler middleware function that is called during an error (e.g., when the next() function is called with an argument). The error should be as follows, where <error> is whatever is the first argument of the error handler:

An error occurred: <error>
Tips
You may complete this challenge on your own machine before uploading it to Qualified.
Reference the related lesson for help on completing this practice problem.
