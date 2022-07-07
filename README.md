# PaintJob
This app is made for painters (not artists tho). Method getBucketCount is overloaded 2 times. It takes as an input:

a) measurments of wall that will be painted (height and width), area that can be painted by one bucket of paint, extra bucket that painter already has

b) measurments of wall that will be painted (height and width), area that can be painted by one bucket of paint

c) area that will be painted, extra bucket that painter already has.

Painter provides getBucketCount with values of type double, and depending on how many values he gives, app does quick maffs, casts result to integer and uses Math.ceil (since if result would be 2.33, you have to buy 3rd bucket).
