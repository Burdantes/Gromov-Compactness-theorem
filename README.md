# Gromov-Compactness-theorem
### Chapter 2 Proof 1 
Let $f:X \to Y$ be a bi-Lipschitz map, then by definition $f$ and $f^{-1}$ are both Lipschitz of constant $K$ and $K'$, hence:
\begin{equation*}
    d_{Y}(f(x_{1}),f(x_{2})) \leq K d_{X}(x_1,x_2)
\end{equation*}
We pick $y_1$ and $y_2$ in $Y$ such that $x_1 = f^{-1}(y_1)$ and $x_2 = f^{-1}(y_2)$, we get:
\begin{equation*}
\begin{split}
    d_Y(y_1,y_2) &\leq K d_{X}(f^{-1}(y_1),f^{-1}(y_2))\leq K K' d_Y(y_1,y_2) \\
\end{split}
\end{equation*}
hence $K'=K^{-1}$. Moreover by picking $y_1 = f(x_1)$ and $y_2=f(x_2)$:
\begin{equation*}
    \begin{split}
        K^{-1} d_X(x_1,x_2) \leq d_Y(f(x_1),f(x_1))
    \end{split}
\end{equation*}
Conversely, let suppose that the equation holds and $f$ invertible, then by applying $f^{-1}$ over $f(x)$, we obtain:
\begin{equation*}
    K d_Y(f^{-1}(x_1),f^{-1}(x_2)) \leq d_X(x_1,x_2)  
\end{equation*}
which concludes the proof
