# SVM
Support Vector Machine
SVM finds a straight line (in 2D) that separates the classes while maximizing the margin to the closest points (support vectors).

We build a simple SVM classifier on trading data (SPY) to predict next day direction using lagged returns.

SVM hyperplane (toy demo)
Purpose: illustrate what a linear SVM learns — one separating line and two margin lines.

Read it:

Solid line = decision boundary where the SVM score = 0.
Dashed lines = margins at score = ±1.
Support vectors lie on or inside the margins and determine the boundary.
The margin width reflects the trade-off set by C (lower C → wider margin, higher C → tighter fit).
This is a geometry demo only. In the SPY section we keep the same 2-feature pipeline and report test accuracy and the confusion matrix; the toy plot builds intuition for what the SVM is doing