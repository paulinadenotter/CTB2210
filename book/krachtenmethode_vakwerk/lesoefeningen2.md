````{margin}
```{attributiongrey} Bronvermelding
:class: attribution

Deze oefening is aangepast van https://oit.tudelft.nl/CT1000/2024/week_3/session_3/intro.html

% Figures from https://github.com/TUDelft-books/CT1000/blob/2024/book/week_3/session_3/intro_data/Tekening1.vsdx

```
```` 

# Begeleide oefening

Gegeven is de volgende constructie:

```{figure} lesoefeningen_2_data/structure.svg
:align: center

Constructie
```

Bepaal de verplaatsingen van de knopen.

:::::{exercise}
:label: vakwerk_1_1
:nonumber: true

```{h5p} https://tudelft.h5p.com/content/1292634971733883797/embed
```

:::::






:::::{exercise}
:label: vakwerk_1_2
:nonumber: true

```{h5p} https://tudelft.h5p.com/content/1292634953266684027/embed
```

:::::






:::::{exercise}
:label: vakwerk_1_3
:nonumber: true

We kiezen voor een statisch onbepaalde kracht $B_{\rm{h}}$ (naar links positief) met de vormveranderingsvoorwaarde $w_{\rm{B,h}} = 0 $.

```{figure} lesoefeningen_2_data/SD.svg
:align: center

Statisch bepaalde constructie met vormveranderingsvoorwaarde
```

Bepaal de normaalkrachten in alle staven als functie van $B_{\rm{h}}$.

```{h5p} https://tudelft.h5p.com/content/1292635090407938947/embed
```

:::::






:::::{exercise}
:label: vakwerk_1_4
:nonumber: true

Bepaal de verlenging/verkorting in alle staven als functie van $B_{\rm{h}}$.

```{h5p} https://tudelft.h5p.com/content/1292635092328991097/embed
```

:::::





:::::{exercise}
:label: vakwerk_1_5
:nonumber: true

Om de verplaatsingen te vinden van de knopen kijken we afzonderlijk naar de invloed van de horizontale kracht $B_{\rm{h}}$ en van de belasting van $20 \ \rm{kN}$. Hiermee worden de Williot-diagrammetjes iets simpeler

We beginnen met de de belasting van $20 \ \rm{kN}$. Daarvoor reken we dus enkel met de volgende verkortingen/verlengingen:

$$\begin{array}{c}
{\Delta {L_{{\rm{AC}}}} =  - 0.025 \ {\rm{ m}}}\\
{\Delta {L_{{\rm{CE}}}} =  - 0.012\ {\rm{ m}}}\\
{\Delta {L_{\rm{BE}}} = \cfrac{1}{{120}} \approx  - 0.00833\ {\rm{ m}}}\\
{\Delta {L_{{\rm{CD}}}} = \cfrac{1}{{120}} \approx  - 0.00833\ {\rm{ m}}}\\
{\Delta {L_{{\rm{DE}}}} = \cfrac{1}{{120}} \approx 0.00833 \ {\rm{ m}}}\\
{\Delta {L_{{\rm{AD}}}} = 0.018 \ {\rm{ m}}}\\
{\Delta {L_{{\rm{DB}}}} = 0.006 \ {\rm{ m}}}
\end{array}$$

De verlengingen/verkortingen ten gevolge van de $20 \ \rm{kN}$ zijn deels gegeven:

| Scharnier | Verplaatsing in horizontale richting → (mm)| Verplaatsing in verticale richting ↓ (mm)|
| :-:|:-:|:-:|
|$\rm{A}$|$0$|$0$|
|$\rm{B}$|?|?|
|$\rm{C}$|$21$|$47$|
|$\rm{D}$|$18$|$\cfrac{233}{6} \approx 39$|
|$\rm{E}$|$9$|$\cfrac{65}{3} \approx 22$|

```{figure} lesoefeningen_2_data/displaced_incomplete.svg
:align: center

Deel van vervormde constructie statisch bepaalde constructie ten gevolge van 20 kN.
```

Bepaal de ontbrekende verplaatsing. Het beginnetje van het williot-diagram is gemaakt:

```{figure} lesoefeningen_2_data/incomplete_williot.svg
:align: center

Incompleet Williot diagram
```

```{h5p} https://tudelft.h5p.com/content/1292635136895634107/embed
```

:::::






:::::{exercise}
:label: vakwerk_1_6
:nonumber: true

Nu gaan we het williot-diagram teken ten gevolge van $B_{\rm{h}}$. Daarvoor reken we dus enkel met de volgende verkortingen/verlengingen:

$$\begin{array}{c}
{\Delta {L_{{\rm{AC}}}} =  \Delta {L_{{\rm{CE}}}} = \Delta {L_{\rm{BE}}} = \Delta {L_{{\rm{CD}}}} = \Delta {L_{{\rm{DE}}}} = 0}\\
{\Delta {L_{{\rm{AD}}}} = - 0.0016{B_{\rm{h}}} \ {\rm{ m}}}\\
{\Delta {L_{{\rm{DB}}}} = - 0.0016{B_{\rm{h}}} \ {\rm{ m}}}
\end{array}$$

Bepaal op basis van deze verlengingen en verkortingen alle verplaatsingen met een apart williot-diagram. Neem daarvoor een zelf gekozen lengte aan voor $B_{\rm{h}}$ (bijvoorbeeld $4$ hokjes komt overeen met $1.6{B_{\rm{h}}}$). Houd daarnaast eerst $\rm{AD}$ in de horizontale oriëntatie zodat je die daarna kan terugdraaien.

```{h5p} https://tudelft.h5p.com/content/1292635148099409217/embed
```

:::::


:::::{exercise}
:label: vakwerk_1_6b
:nonumber: true

Als het goed is heb je gevonden dat $\rm{B}$ $2.4 B_{\rm{h}}$ verticaal naar beneden verplaatst. Draai onze vastgehouden $\rm{AD}$ nu zo terug dat $\rm{B}$ niet meer verticaal verplaatst.

```{h5p} https://tudelft.h5p.com/content/1292635150038900187/embed
```

:::::




:::::{exercise}
:label: vakwerk_1_7
:nonumber: true


```{h5p} https://tudelft.h5p.com/content/1292635153881798987/embed
```

:::::







:::::{exercise}
:label: vakwerk_1_8
:nonumber: true

Gebruik je resultaat om de normaalkrachten in alle staven te vinden.

```{h5p} https://tudelft.h5p.com/content/1292635156869126557/embed
```

:::::







Als je alles goed hebt gedaan zou je op de volgende verplaatsingen uit moeten komen

| Scharnier | Verplaatsing in horizontale richting → (mm)| Verplaatsing in verticale richting ↓ (mm)|
| :-:|:-:|:-:|
|$\rm{A}$|$0$|$0$|
|$\rm{C}$|$9$|$38$|
|$\rm{D}$|$6$|$29.833$|
|$\rm{E}$|$-3$|$12.66$|
|$\rm{B}$|$0$|$0$|

```{figure} lesoefeningen_2_data/displaced3.svg
:align: center

Vervormde constructie
```
