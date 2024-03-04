# A simple date counter app with React, primarily focusing on using the useState hook.

The step value decides how far we go back or forward in dates.
## What buggled me most and what I've learned was, using the callback functions in event handlers;
We use them because;
- In React, state updates may be asynchronous, meaning that the state value (c in this case) might not immediately reflect the latest value when the update is made.
- By using a function that takes the previous state (c) as an argument, we are guaranteed to have the most current state value at the time the update is applied.

![chrome_EqPCuDZmKK](https://github.com/polarbeerd/datecounterv1/assets/76842287/ff232d12-e528-458f-a5fe-76f5500e7bc1)

