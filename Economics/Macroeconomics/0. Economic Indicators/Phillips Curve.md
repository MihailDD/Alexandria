>[!note] Phillips Curve
>The Phillips curve is an economic model developed by A. W. Phillips that states that unemployment and inflation have an inverse relationship, such that
>$$\pi_t=\pi_{E_{t+1}}-\alpha(U_t-U_{N_t}) + shock_t.$$
>where $U$ and $U_N$ are the current and natural unemployment rates, whereas $\pi$ and $\pi_E$ are the current and expected inflation rates. Graphically,
>```tikz
>\begin{document}
>  \begin{tikzpicture}[domain=0:4]
>    \draw[->] (0,0) -- (4.2,0) node[right]{$U$};
>    \draw[->] (0,0) -- (0,4.2) node[above]{$\pi$};
>    \draw[] (0.5, 3.75) arc (190:275:3 and 4) node[right]{Phillips curve};
>   \end{tikzpicture}
>\end{document}
>```
>The Phillips curve suggests that when inflation meets expectations ($\pi=\pi_E$), unemployment is at its natural level ($U=U_N$).



