Transaction cost regularization for online portfolio selection

To further improve the performance of the online portfolio considering transaction costs, we propose a transaction cost regularization (TCR) model. This model minimizes the negative expected return and meanwhile incorporates the L1 norm of the difference between two consecutive allocations as a regularization term to control the transaction cost. We first apply the linearized augmented Lagrangian method to solve the proposed model and derive a convergent iterative algorithm whose update in each iteration has a closed-form, which enable the computational efficiency of the algorithm. To further study the problem, the alternative direction method of multipliers is applied to solve the portfolio model and its convergence is theoretically guaranteed as well as guaranteeing that the portfolio variables for each iteration are constrained in simplex. Numerical experiments on benchmark datasets illustrate that our proposed algorithms are efficient and can achieve higher cumulative wealth than the compared state-of-the-art algorithms in most cases.

The source code is provided "as is" without warranty of any kind, and its author disclaims any 
and all warranties, including but not limited to any implied warranties of merchantability 
and fitness for a particular purpose, and any warranty or non infringement. The user assumes all responsibilities 
and obligations for the use of this source code, and the author is not responsible for any kind of damage 
caused by the use of this source code. Without limiting the generality of the above, the author 
does not guarantee that the source code will be error-free, will operate without interruption, 
or will meet the needs of the user.
  
This function is the main code for portfolio optimization in a non-zero transaction cost environment 
based on the linearized augmented Lagrangian method. Based on some empirical financial principles 
and optimization strategies, it uses elastic-net regularization terms to consider the correlation 
between transaction costs and variables, thereby maximizing the cumulative wealth in the entire investment 
while reducing transaction costs.
