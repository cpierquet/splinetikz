# splinetikz

Quelques macros pour créer, en TikZ, des courbes d'interpolations et des tangentes.

La commande <code>\splinetikz[...]</code>, trace un ensemble de <i>splines</i> grâce notamment à une liste de points sous la forme <code>x1/y1/d1§x2/y2/d2§...</code> et une liste des coefficients de <i>compensation</i> sous la forme d'une liste <code>C1G/C1D§C2G/C2D§...</code> (qui peut être plus simple !).

Également de quoi tracer, grâce à la commande <code>\tangentetikz[...]</code>, des tangentes à l'aide de triplets <code>xa/ya/da§...</code> pour tracer une (portion de) tangente via <code>da*(x-xa)+ya</code>.

![illustr](splinetikz.png?raw=true "Title")
