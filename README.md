# Excercise - Debugging 2
### Winter 2017 - Android

### Overview:
Learn how to use log statements and the debugger to understand how this complex app works.
<br>
This exercise is a variant of Google's "Sunshine" app in the "Developing Android Apps" e-course from Udacity.

### Getting Started:

1. Clone repository.
2. Create a new branch off master and name the branch according to the form {name}/debugging2 (e.g. mgroves/debugging2).

### Your Task:

1. Run the app.
2. Look in the Android Monitor for the URL of the network request that is being made.
3. What does the weather data look like that is coming from this network request?  Add a log statement at the appropriate place in the code and re-run the app.  Think about what logging level this should use.


4. Now, let the app run for at least a minute.
5. Why is the network request logged multiple times?  Try adding a breakpoint to see where this is getting called from.
6. Show your work by writing comments as you trace the execution flow through the app.  This is hard, so don't feel discouraged if you don't find it.
7. When you discover why network requests are happening multiple times, change the code so this only happens once.
8. Create a pull request against master with your solution.
