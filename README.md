This repository contains all the files necessary to replicate the experiments in the article:

Bishnu P. Lamichhane, Scott B. Lindstrom, and Brailey Sims, "Application of Projection Algorithms to Differential 
Equations: Boundary Value Problems." ANZIAM, (2019) 61(1), 23-46.

File descriptions are as follows.

The following Maple worksheets generate numerical solutions corresponding to the discretized problem (via Newton's
method), as well as solutions corresponding to the true solutions. These are used for comparison in performance plots.

Example 6.1: Book_solutions
Example 6.2: BraileyAbs_solutions
Example 6.3: Jump_solutions
Example 6.4: PaperAbs_solutions
Example 6.5: Exp_solutions
Example 6.6: Heaviside_solutions

The following Maple worksheets may be used to generate the error plots.

Example 6.1: BookR
Example 6.2: BraileyAbsR
Example 6.3: JumpR
Example 6.4: PaperAbsR
Example 6.5: ExpR
Example 6.6: HeavisideR

-------------------------

Description of Four_Methods

This final, exceptional Maple Worksheet, may be used to run an experiment that is not found in the original article.
It allows for comparison of the performance of alternating projections and Douglas--Rachford with
two other methods: CRM and LT. This application of CRM (circumcentered reflections method) is used in:

Neil Dizon, Jeffrey Hogan, and Scott B. Lindstrom, "Circumcentering Reflections for Nonconvex Feasibility Problems," (2020).

The method LT was introduced in:

Scott B. Lindstrom, "Computable Centering Methods for Spiraling Algorithms and their Duals, with Motivations from the 
Theory of Lyapunov Functions," (2020). 
