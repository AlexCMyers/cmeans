# Cmeans calculations in multiple programming paradigms
This repositity contains code to calculate cmeans in Ocaml (functional programming) and in prolog (declarative/logical programming)

cmeans is a math problem that can be phrased as follows:
"When given a group of points and an integer C less than or equal to the number of given points, what are the centers of C clusters that best represent the inputted points?"

In other words, it involves finding C locations where the average distance from any of the inputted points to the closest of those C locations is as low as possible.

For example, if the set of points is [[6, 6], [8,8], [-6, -6], [-8,-8]] and C=2, then the results of the cmeans algorithms would be [[7,7].[-7,7]].
If, instead, C=1, then the result would be [[0,0]], as that is the avergae of all of the points in the set.

Running Ocaml:


Running Prolog:
