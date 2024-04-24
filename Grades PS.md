## Grades PS:

PS1: 8.25/10. Great job.

PS2: 7.5/10. Great job! See my solutions, you had some comments and potentially some graphs/computations incorrect. For example, the monetary variables were in US dollars not Ugandan Shillings!! and the exchange rate is around 1$ - 3000 USh

PS3: 7.25, excellent. You missed some computations and comments in ex1 and ex2.

PS4: 7.5/10, excellent. Check exercise 1. At optimization problems you need to provide the solution, the vector x*. Also note that Nelder-Mead does not converge so it is actually the algorithm doing worse for this particular exercise (and given the x0).

### PS5: 7.5/10
(a) Nice discussion of RMSE, but main results are incorrect.  Main problem seems
to be that RMSE is far too high.  Probably because you're comparing the gradient
with the hessian, rather than calculating the difference between what you get
with FDM and ForwardDiff...  In (iii) I don't understand the results you're
showing -- shouldn't proportion_converged be in (0,1)?  Otherwise results look
mostly correct.  

(b-c) Nothing looks wrong here, but it's quite hard to interpret your results.
You'll want to do more to structure them in a sensible and readable way.  

(d) Not sure what the comment about tolerances is about.  I don't think it
follows from the analysis you've done. 

Otherwise, good job on a hard problem set

PS6: 6.5/10
Your use of interpolation techniques shows a good grasp of numerical methods,
particularly in function approximation. However, there's room for improvement in
interpreting the implications of the errors associated with these methods,
especially in the context of economic modeling. I want to see more
discussion/analysis.  Be careful about running things in global scope
(especially with your Chebyshevev implementation). The presentation of results
could be more coherent -- be more structured in your analysis.

PS7: 7.25/10
Good job on Q1, although some of your policies look rather noisy, even for linear interpolation.  Are you solving the max problem correctly?
I'm getting different revenues than you in Q2.  Check against the solutions manual.  

PS8: 8.5/10.  Really well done.  You've absolutely nailed it.  