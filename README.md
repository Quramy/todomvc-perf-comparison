# TodoMVC Performance Comparison
This repository was forked from https://github.com/evancz/todomvc-perf-comparison/ , and I modified:

+ version up AngularJS
+ add [Facebook flux React](https://github.com/facebook/flux/tree/master/examples/flux-todomvc) to test suite

Both Mercury and Elm are based on the [virtual-dom][] project which appears to
be extremely fast.

[virtual-dom]: https://github.com/Matt-Esch/virtual-dom

[**Run it yourself**][runner] to see how it works on your machine or in other
browsers!

Here are some sample results from running this in Chrome 35 with OSX 10.9.4 on
a Macbook Air:

[![Sample results for Chrome 35 + OSX 10.9.4 on a Macbook Air](sampleResults.png)][runner]

[runner]: http://Quramy.github.io/todomvc-perf-comparison/
