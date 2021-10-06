A well-typed program is noninterferent at $\tau$ for $\Gamma$. 

\begin{theorem}

Let $\Gamma$ be a typing environment and $\tau \in \mathcal{L}$ a security label. If $\Gamma \vdash p$ then $p$ is $NI^{\Gamma}_\tau$.

\end{theorem}


We prove this theorem by induction on the height of the typing derivation tree of $\Gamma \vdash p$. 
