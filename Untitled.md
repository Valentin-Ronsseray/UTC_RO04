Pour la partie $x \to -\infty$, on reprend l'expression de départ et on peut la réécrire de la manière suivante :
$$
\begin{align}
x + 2 - \sqrt{ x^{2} + 4x }  & = (x + 2) + (-\sqrt{ x^{2} + 4x })
\end{align}
$$
Or $x - 2 \xrightarrow[x \to - \infty]{}-\infty$.
De plus $-\sqrt{ x^{2} + 4x } \xrightarrow[x \to -\infty]{}-\infty$ (car $x^{2} + 4x \xrightarrow[x \to -\infty]{}+\infty$ et $-\sqrt{ u } \xrightarrow[u \to+\infty]{}-\infty$ : on obtient la limite de ce terme par composition de fonctions **continues**).
Donc par somme de limites (la forme $(-\infty) + (-\infty)$ n'étant pas indéterminée), la quantité $x + 2 - \sqrt{ x^{2} + 4x }$ admet une limite quand $x \to -\infty$ et
$$
\boxed{ \lim_{ x \to -\infty } x + 2 - \sqrt{ x^{2} + 4x } = -\infty }
$$
