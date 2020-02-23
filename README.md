The Basic Tipping Problem
This example creates a Mamdani fuzzy inference system using on a two-input, one-output tipping problem based on tipping practices in the U.S. While the example creates a Mamdani FIS, the methods used apply to creating Sugeno systems as well.

Given a number between 0 and 10 that represents the quality of service at a restaurant (where 10 is excellent), and another number between 0 and 10 that represents the quality of the food at that restaurant (again, 10 is excellent), what should the tip be?

The starting point is to write down the three golden rules of tipping:

If the service is poor or the food is rancid, then tip is cheap.

If the service is good, then tip is average.

If the service is excellent or the food is delicious, then tip is generous.

Assume that an average tip is 15%, a generous tip is 25%, and a cheap tip is 5%.
