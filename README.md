# Exercise Set 1 for the Financial Markets Course


Exercise 1)

i)
By strict prefference x $\succ$ x => x $\succsim$ x but not x $\precsim$ x, the it must be a contradiction such that x $\succ$ x does not holds. Let x $\prec$ y and y $\prec$ z and x $\neq$ z. Then x $\precsim$ y and y $\precsim$ z and thus x $\precsim$ z. Since x $\neq$ z then x $\prec$ z and transitivity has been proven.

ii)
Let's consider x $\succsim$ x and x $\precsim$ x and since $\succsim$ is rational, then it yields x $\sim$ x $\forall$x $\in$ X. 
Let x $\sim$ y and y $\sim$ z. Since it's known that x $\precsim$ y and y $\precsim$ z $\Rightarrow$ x $\precsim$ z and thus x $\sim$ z.
Let x $\sim$ y. It's known that if x $\succsim$ y and x $\precsim$ y then x $\sim$ y. Thus y $\sim$ x. 

iii)
Since $\succsim$ is raional it is transitive, so if x $\succ$ y $\succsim$ z, then by transitivity x $\succ$ z. 

Exercise 2)

i)
If we have $(x_1,x_2)\succsim (y_1,y_2)$ and $(y_1,y_2)\succsim (z_1,z_2)$, and 
$x_1\succ y_1$ or $x_1 \sim y_1$ and $x_1 \succsim y_1$. 
If $x_1\succ y_1$ we have $x_1\succ y_1 \succ z_1$ and therefore $(x_1,x_2)\succsim (y_1,y_2)\succsim (z_1,z_2)$.
If $x_1 \sim y_1$ and $x_1 \succsim y_1$ we have $x_1 \sim y_1 \sim z_1$ and $x_1 \succsim y_1 \succsim z_1$ therefore $(x_1,x_2)\succsim (y_1,y_2)\succsim (z_1,z_2)$
We now know that 


ii)
By considering the sequence $(x_1^n, x_2^n)=(1-1/n,1) and (y_1,y_2)=(1,0)$.
Because $\lim_{n \to \infty}(x_1^n, x_2^n)=(1,1)$ the prefrences changes as the limit goes to $\infty$ therefore $\succsim$ is not continuous.    


Exercise 3)

i)
When $\rho=1$:
Show that $U(x+y)=U(x)+U(y)$
$(\alpha_1(x_1+y_1)+\alpha_2(x_2+y_2))=(\alpha_1x_1+\alpha_2x_2+\alpha_1y_1+\alpha_2x_2)=U(x)+U(y)$

Show that $U(cx)=cU(x)$
$(c\alpha_1x_1+c\alpha_2x_2)=c(\alpha_1x_1+\alpha_2x_2)=cU(x)$

ii)
$U(x)=(\alpha_1x_1^{\rho}+\alpha_2x_2^{\rho})^{1/{\rho}}$,
$ln(U)=\lim_{\rho \to \infty}(\frac{ln(\alpha_1x_1^p+\alpha_2x_2^p)}{\rho})$
$=\frac{\alpha_1x_1^{\rho}ln(x_1)+\alpha_2x_2^{\rho}ln(x_2)}{\alpha_1x_1^{\rho}+\alpha_2x_2^{\rho}}$
$=\frac{ln(x_1^{\alpha_1}x_2^{\alpha_2})}{\alpha_1+\alpha_2}$
taken the inverse of ln, we get $x_1^{\alpha_1}x_2^{\alpha_2}$. 
It means that the utility function U(x) represent the same preferences as the generalized Cobb-Douglas function.  


iii)

iv)

v)



