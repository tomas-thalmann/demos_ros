Wanderer
========

Implementation of a simple wanderer taking the path with the farthest distance
(e.g., by analyzing the scan of the laser range finder).

* *TODO* Formulate the problem (wandering into the direction of the farthest
  distance) as simple decision making. What is the utility function? What is
  the decision network (random variables used, utility, decision)? Explain.
* *TODO* Implement the decision making process in a ROS node. Map the
  formulated decision maker to the code (formulas/evalutions/decisions to parts
  of the code).
* *TODO* State and explain the decision maker and the implementation.

Setup
-----

* *TODO* What devices are used? What should be powered on?
* *TODO* What settings do you need on the devices? (e.g., on the rover, what
  sensors have to be connected?)

Usage
-----

* *TODO* Which ROS nodes have to be started? Provide the necessary commands
  here. Put links to the sources of the started ROS nodes.
* *TODO* Write a launch file that starts all the necessary nodes for
  demonstration
  ([roslaunch](http://wiki.ros.org/roslaunch),
  [launch file format](http://wiki.ros.org/roslaunch/XML)). It is then enough
  to show, how to start the launch file -- optional (10 bonus points)
* *TODO* Describe parameters, if available or needed (e.g., serial port,
  modes).
* *TODO* Finally remove all the TODOs.

```bash
$ roscore &
:
:
```


(you can delete everything below and all todos when you're done)

Organizational Notes
--------------------

Finally, this repo shall include:
* A `src` folder containing the implementation.
* This README with answered questions and copy-and-paste instructions for how
  to start the demo (ROS nodes, topic redirects if necessary). In the best
  case, only a ROS launch file has to be executed. However, a list of commands
  is also ok.
* Optional launch file (please put into a folder called `launch`).

### Grading

| Points |                     |
|-------:|---------------------|
|     40 | problem formulation |
|     40 | implementation      |
|     20 | docs in this README |
|    +10 | launch file         |
