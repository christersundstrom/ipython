
## Vektorer

| Begrepp        | Algebra   | Geometri | Beteckning
| -------------- |:-----------------------------------:| ------------------------------------------------------------------ | ----------------:|
| Riktad sträcka | ett par av punkter $(A,B)$          | en riktad sträcka mellan två bestämda punkter i ett kordinatsystem | $\\overline{AB}$ |
| Vektor         | en ordnad lista av tal, t ex $(5,3,2)$ | en riktad sträcka som kan förflyttas parallellt | $\\bar{u}$    |
|   ...          | en matris med en kolumn $\\begin{pmatrix}5 \\\\ 3 \\\\ 2 \\end{pmatrix}$ |  en mängd riktade sträckor med samma längd och riktning             |    |

### Addition av vektorer

Vektorer kan adderas algebraiskt:  
$$
\\begin{gather}
\\bar{u} = (a,b) \\\\
\\bar{v} = (c,d)  \\\\
\\bar{u} + \\bar{v} = (a,b) + (c,d) = (a+c, b+d)
\\end{gather}  
$$

Eller adderas geometriskt $\\bar{u} + \\bar{v}$:  
*   Placera  $\\bar{u}$ i kordinatsystem med start i origo.  
*   Placera $\\bar{v}$ med start i spetsen på $\\bar{u}$.  
*   Summan blir en vektor från origo till spetsen på $\\bar{v}$.

### Subtraktion av vektorer

Vektorer kan subtraheras algebraiskt:  
$$
\\begin{gather}
\\bar{u} = (a,b) \\\\
\\bar{v} = (c,d)  \\\\
\\bar{u} - \\bar{v} = (a,b) - (c,d) = (a-c, b-d)
\\end{gather}  
$$

Eller subtraheras geometriskt $\\bar{u} - \\bar{v}$:  
*   Placera  $\\bar{u}$ i kordinatsystem med start i origo.  
*   Rikta om $\\bar{v}$ åt motsatt håll, placera den med start i spetsen på $\\bar{u}$.  
*   Differensen  blir en vektor från origo till spetsen på den omriktade $\\bar{v}$.


### Produkt av ett tal och en vektor

En vektor multipliceras med ett tal algebraiskt:  
$$
\\begin{gather}
\\bar{u} = (a,b) \\\\
\\lambda \\bar{u} = \\lambda (a,b) = (\\lambda a, \\lambda b)
\\end{gather}  
$$


### Linjärkombination av vektorer

Att addera vektorer där varje vektor dessutom multipliceras med valfri skalningsfaktor kallas linjärkombination.  

Algebraiskt:  
$$
\\begin{gather}
\\bar{u} = (a,b) \\\\
\\bar{v} = (c,d)  \\\\
\\omega = \\lambda \\bar{u} + \\mu \\bar{v} = (\\lambda a + \\mu c, \\lambda b + \\mu d)
\\end{gather}  
$$

### Skalärprodukt

Definition av skalärprodukt mellan två vektorer $\\bar{u}$ och $\\bar{v}$ med vinkeln $\\phi$ mellan:  

$$
\\bar{u} \\cdot \\bar{v} = \\left\\vert \\bar{u} \\right\\vert \\left\\vert \\bar{v} \\right\\vert \\cos \\phi
$$

Skalärprodukt i ortonormerad bas:

$$
\\begin{gather}
\\bar{u} = (a_1,a_2,a_3) \\\\
\\bar{v} = (b_1,b_2,b_3)  \\\\
\\bar{u} \\cdot \\bar{v} = a_1 b_1 + a_2 b_2 + a_3 b_3
\\end{gather}  
$$



