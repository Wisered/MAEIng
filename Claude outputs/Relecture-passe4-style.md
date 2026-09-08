# Passe 4 — rythme et voix — `chapters/chapitre4.tex`

*Établie le 8 septembre 2026. Passe de style seule : le fond, les chiffres et les citations
ne sont pas rouverts. Trente-deux corrections, toutes* `RECOMMANDÉ` *— aucune n'est*
`BLOQUANT` *(le fond est validé), aucune n'est* `COSMÉTIQUE` *(chacune traite l'un des deux
défauts visés). Aucun fichier n'a été modifié.*

**Mesures avant / après application des trente-deux corrections**, faites sur le fichier
source :

| Mesure | Avant | Après |
|---|---|---|
| Tirets cadratins `---` | 36 | 4 (titres de section) |
| Phrases de plus de 45 mots | 30 | 0 |
| Tournures « il ne s'agit pas de X mais de Y » | 2 | 0 |
| `\cite` / `\ref` / `\label` / `\textbf` | 18 / 1 / 1 / 6 | inchangés |
| Fragments entre guillemets `«~…~»` | 21 | 21, à l'identique |
| Codes de grille, codes de répondants, chiffres | 28 / 84 / 47 | inchangés |
| Contenu du `tabular` | — | inchangé |

---

## Corrections

---
**1 — RECOMMANDÉ — `chapters/chapitre4.tex` — page 39**

*AVANT* :
```latex
La restitution suit les axes de la grille reproduite en annexe~B et non l'ordre des
répondants~: la matrice croisant les codes et les répondants \cite{miles2003} ne produit de
résultat que lue en lignes, sur ce qui converge, ce qui sépare et ce qui n'apparaît qu'une
fois. Un constat est dit \textbf{saturé} lorsque les cinq récits le documentent,
\textbf{clivant} lorsque le matériau se scinde entre deux postures, \textbf{isolé} lorsqu'un
seul répondant le rapporte --- il est alors conservé, mais sans portée générale.
```

*APRÈS* :
```latex
La restitution suit les axes de la grille reproduite en annexe~B et non l'ordre des
répondants. La matrice croisant les codes et les répondants \cite{miles2003} ne produit de
résultat que lue en lignes, sur ce qui converge, ce qui sépare et ce qui n'apparaît qu'une
fois. Un constat est dit \textbf{saturé} lorsque les cinq récits le documentent,
\textbf{clivant} lorsque le matériau se scinde entre deux postures, \textbf{isolé} lorsqu'un
seul répondant le rapporte. Il est alors conservé, mais sans portée générale.
```

*Pourquoi* : coupe une phrase de 46 mots et supprime un cadratin, en ouvrant le chapitre sur deux affirmations au lieu d'une seule période.

---
**2 — RECOMMANDÉ — `chapters/chapitre4.tex` — pages 39–40**

*AVANT* :
```latex
La sanctuarisation est saturée, et sa frontière l'est aussi. La zone que chacun ne délègue
pas se définit par la sensibilité des données et par la nécessité d'un contexte que l'outil
n'a pas connu, non par la difficulté de la tâche~: les données chiffrées
confidentielles pour J1 --- «~dealbreaker~»~---, l'analyse conduite après un exercice de
crise pour J2, au motif noté que «~l'IA n'était pas dans la salle~», l'architecture de
sécurité, les vulnérabilités et les données classifiées réservées à la «~main humaine~» par
E3, les sujets spécifiques et sensibles pour E2, les choix engageant une recommandation ou
une orientation pour E1. Les missions diffèrent~; la frontière, elle, ne varie pas.
```

*APRÈS* :
```latex
La sanctuarisation est saturée, et sa frontière l'est aussi. La zone que chacun ne délègue
pas se définit par la sensibilité des données et par la nécessité d'un contexte que l'outil
n'a pas connu, non par la difficulté de la tâche. Ce sont les données chiffrées
confidentielles pour J1 («~dealbreaker~»), l'analyse conduite après un exercice de crise
pour J2, au motif noté que «~l'IA n'était pas dans la salle~». Pour E3, ce sont
l'architecture de sécurité, les vulnérabilités et les données classifiées réservées à la
«~main humaine~»~; pour E2, les sujets spécifiques et sensibles~; pour E1, les choix
engageant une recommandation ou une orientation. Les missions diffèrent~; la frontière,
elle, ne varie pas.
```

*Pourquoi* : la phrase la plus longue du chapitre, 91 mots, est ramenée à trois phrases, et les deux cadratins encadrant «~dealbreaker~» passent en parenthèses.

---
**3 — RECOMMANDÉ — `chapters/chapitre4.tex` — page 40**

*AVANT* :
```latex
Le seuil de spécificité est le deuxième constat saturé, et il est chiffré par tous~: vingt
minutes de reformulations de consignes sans résultat exploitable puis quinze minutes de
rédaction directe pour J1, sur un sujet où l'outil renvoyait à des textes inexistants~; dix
minutes puis cinq pour J2~; quarante-cinq minutes de reprise pour E3 sur une reformulation
où deux concepts clés avaient été intervertis, contre vingt minutes en production directe~;
une nuit pour E1, à reprendre un livrable client intégralement produit avec assistance.
```

*APRÈS* :
```latex
Le seuil de spécificité est le deuxième constat saturé, et il est chiffré par tous. J1
compte vingt minutes de reformulations de consignes sans résultat exploitable puis quinze
minutes de rédaction directe, sur un sujet où l'outil renvoyait à des textes inexistants.
J2 compte dix minutes puis cinq. Pour E3, quarante-cinq minutes de reprise sur une
reformulation où deux concepts clés avaient été intervertis, contre vingt minutes en
production directe. Pour E1, une nuit à reprendre un livrable client intégralement produit
avec assistance.
```

*Pourquoi* : 83 mots ramenés à cinq phrases, en coupant aux points-virgules qui séparaient déjà les quatre répondants.

---
**4 — RECOMMANDÉ — `chapters/chapitre4.tex` — page 40**

*AVANT* :
```latex
Le troisième constat saturé contredit l'intuition ordinaire du gain de productivité~: le
temps gagné ne sort pas de la boucle de production, il se déplace de la rédaction vers la
vérification --- deux heures en trois relectures pour J1, deux heures en recoupement croisé
des sources pour E3, une heure en contrôle de cohérence pour J2, E1 énonçant que le gain
devrait y être affecté. L'exception vient du répondant le plus utilisateur~: E2 réinvestit ce
temps dans la relation client, le c\oe{}ur du métier étant selon ses notes de comprendre et
non de produire.
```

*APRÈS* :
```latex
Le troisième constat saturé contredit l'intuition ordinaire du gain de productivité~: le
temps gagné ne sort pas de la boucle de production, il se déplace de la rédaction vers la
vérification. Le déplacement est chiffré~: deux heures en trois relectures pour J1, deux
heures en recoupement croisé des sources pour E3, une heure en contrôle de cohérence pour J2,
E1 énonçant que le gain devrait y être affecté. L'exception vient du répondant le plus
utilisateur~: E2 réinvestit ce temps dans la relation client, le c\oe{}ur du métier étant
selon ses notes de comprendre et non de produire.
```

*Pourquoi* : 64 mots coupés en deux, l'énumération chiffrée étant reprise par une amorce courte à la place du cadratin.

---
**5 — RECOMMANDÉ — `chapters/chapitre4.tex` — pages 40–41**

*AVANT* :
```latex
l'ouverture de l'accès à l'outil homologué. Deux répondants l'évoquent~: E1, sous la forme
d'une session de sensibilisation qu'il n'a pas approfondie, et J1, sous celle d'une session
rappelant les règles d'usage de l'outil homologué et d'un webinaire qu'une mission l'a
empêché de suivre~; aucun ne la désigne comme le
canal par lequel il a appris à se servir de l'outil. Le corpus confirme ainsi par son
silence ce que le chapitre~1 établit par la description du dispositif~: l'encadrement
porte sur l'entrée dans l'usage, non sur l'usage lui-même. Une exception doit cependant être
signalée, et elle vient de l'extérieur du cabinet~: E3 suit
depuis plusieurs mois une certification externe, engagée de sa propre initiative et motivée
par la demande des clients, dont il note qu'elle vaut autant comme document à valoriser que
comme apprentissage, et sur laquelle il revient plus tard dans l'entretien, en évoquant sa formation continue.
```

*APRÈS* :
```latex
l'ouverture de l'accès à l'outil homologué. Deux répondants l'évoquent~: E1, sous la forme
d'une session de sensibilisation qu'il n'a pas approfondie, et J1, sous celle d'une session
rappelant les règles d'usage de l'outil homologué et d'un webinaire qu'une mission l'a
empêché de suivre. Aucun ne la désigne comme le canal par lequel il a appris à se servir de
l'outil. Le corpus confirme ainsi par son silence ce que le chapitre~1 établit par la
description du dispositif~: l'encadrement porte sur l'entrée dans l'usage, non sur l'usage
lui-même. Une exception doit cependant être signalée, et elle vient de l'extérieur du
cabinet. E3 suit depuis plusieurs mois une certification externe, engagée de sa propre
initiative et motivée par la demande des clients. Il note qu'elle vaut autant comme document
à valoriser que comme apprentissage, et il y revient plus tard dans l'entretien, en évoquant
sa formation continue.
```

*Pourquoi* : deux phrases de 54 et 60 mots coupées, la seconde en trois temps, et le paragraphe est reflué à la largeur du fichier.

---
**6 — RECOMMANDÉ — `chapters/chapitre4.tex` — page 41**

*AVANT* :
```latex
E1 estime que
les juniors doivent avoir fait les tâches ingrates une ou deux fois à la main, faute de quoi
ils ne sauront pas juger ce que l'outil produit~; E2 décrit la même séquence et ajoute que
déléguer sans avoir jamais produit interdit d'évaluer~; E3 déplace le critère sur la
définition du métier, un bon consultant étant celui qui sait ce qu'il met dans ses livrables
et non celui qui sait formuler une consigne.
```

*APRÈS* :
```latex
E1 estime que
les juniors doivent avoir fait les tâches ingrates une ou deux fois à la main, faute de quoi
ils ne sauront pas juger ce que l'outil produit. E2 décrit la même séquence et ajoute que
déléguer sans avoir jamais produit interdit d'évaluer. E3 déplace le critère sur la
définition du métier, un bon consultant étant celui qui sait ce qu'il met dans ses livrables
et non celui qui sait formuler une consigne.
```

*Pourquoi* : 75 mots ramenés à trois phrases, une par encadrant, sans toucher aux formulations.

---
**7 — RECOMMANDÉ — `chapters/chapitre4.tex` — page 41**

*AVANT* :
```latex
L'effet sur le raisonnement du junior est en revanche clivant. J1 documente sur lui-même ce
que la grille prévoyait d'observer~: il se dit «~plus relecteur que rédacteur~», qualifie
d'«~illusion de compétence~» la maîtrise apparente que donne un support produit vite, et
formule son inquiétude sous forme d'échéance, se demandant s'il saura encore, dans six mois,
«~faire structure seul~». J2, à ancienneté comparable, ne partage pas ce diagnostic --- la différence tenant
vraisemblablement à la nature des tâches, créatives et non factuelles chez lui.
```

*APRÈS* :
```latex
L'effet sur le raisonnement du junior est en revanche clivant. J1 documente sur lui-même ce
que la grille prévoyait d'observer. Il se dit «~plus relecteur que rédacteur~» et qualifie
d'«~illusion de compétence~» la maîtrise apparente que donne un support produit vite. Il
formule son inquiétude sous forme d'échéance, se demandant s'il saura encore, dans six mois,
«~faire structure seul~». J2, à ancienneté comparable, ne partage pas ce diagnostic. La
différence tient vraisemblablement à la nature des tâches, créatives et non factuelles chez
lui.
```

*Pourquoi* : coupe une phrase de 49 mots en trois et supprime un cadratin en rendant le participe à un verbe conjugué.

---
**8 — RECOMMANDÉ — `chapters/chapitre4.tex` — page 42**

*AVANT* :
```latex
J1 parle de sujet tabou~; J2
juge la mention sans apport~; E3 la juge non pas dissimulatrice mais contre-productive, le
client payant une expertise et non un outil~; E1, interrogé par des clients, répond que
l'analyse finale et les recommandations reviennent aux équipes, ce qui est exact, mais
indique qu'il ne dirait jamais qu'un support a été produit avec l'outil.
```

*APRÈS* :
```latex
J1 parle de sujet tabou~; J2
juge la mention sans apport. E3 la juge non pas dissimulatrice mais contre-productive, le
client payant une expertise et non un outil. E1, interrogé par des clients, répond que
l'analyse finale et les recommandations reviennent aux équipes, ce qui est exact. Mais il
indique qu'il ne dirait jamais qu'un support a été produit avec l'outil.
```

*Pourquoi* : 60 mots ramenés à quatre phrases, le contraste final sur E1 gagnant à être isolé.

---
**9 — RECOMMANDÉ — `chapters/chapitre4.tex` — page 42**

*AVANT* :
```latex
Ce que les répondants connaissent est un cadre de confidentialité et une liste d'outils
homologués, non une doctrine d'usage --- le chapitre~1 rappelle qu'il n'existe pas de
politique écrite en la matière~---, et tous le jugent insuffisant, pour deux raisons
opposées. Pour les uns, la règle est floue sur son
périmètre~: J1 la décrit comme un flou total s'agissant des outils non homologués et
qualifie ce flou de «~dangereux~», E1 juge les règles «~un peu légères~». Pour les autres,
elle est claire mais muette sur l'essentiel~: E2, qui la trouve «~trop timide~», observe
qu'elle autorise et interdit des outils sans rien dire de la manière de vérifier ce qu'ils
produisent, et E3 la trouve générale au point d'appliquer une règle plus stricte.
```

*APRÈS* :
```latex
Ce que les répondants connaissent est un cadre de confidentialité et une liste d'outils
homologués, non une doctrine d'usage. Le chapitre~1 rappelle qu'il n'existe pas de politique
écrite en la matière. Tous le jugent insuffisant, pour deux raisons opposées. Pour les uns,
la règle est floue sur son périmètre~: J1 la décrit comme un flou total s'agissant des
outils non homologués et qualifie ce flou de «~dangereux~», E1 juge les règles
«~un peu légères~». Pour les autres, elle est claire mais muette sur l'essentiel. E2, qui la
trouve «~trop timide~», observe qu'elle autorise et interdit des outils sans rien dire de la
manière de vérifier ce qu'ils produisent. E3 la trouve générale au point d'appliquer une
règle plus stricte.
```

*Pourquoi* : supprime les deux cadratins encadrant le renvoi au chapitre~1 et coupe la phrase de 46 mots sur E2 et E3.

---
**10 — RECOMMANDÉ — `chapters/chapitre4.tex` — page 43**

*AVANT* :
```latex
D'une part, les incidents ne remontent pas~: celui de J1 a été raconté à un collègue de même
niveau, sur le registre de la plaisanterie, et n'a jamais été porté à la connaissance de son
encadrante, pour un motif que les notes consignent comme la honte et la crainte d'un reproche
d'inattention. D'autre part, le contrôle s'adapte, mais individuellement et après coup. E1
contrôle désormais le processus et non plus le seul contenu final, demandant ce qui relève du
collaborateur, ce qui relève de l'outil et si les sources ont été vérifiées~; E3 a formalisé
pour lui-même un contrôle en trois temps --- cohérence interne, contrôle croisé des sources,
test de défendabilité devant le client~; E2, qui n'a pas vécu d'incident marquant, indique ne
pas contrôler différemment un contenu assisté.
```

*APRÈS* :
```latex
D'une part, les incidents ne remontent pas. Celui de J1 a été raconté à un collègue de même
niveau, sur le registre de la plaisanterie, et n'a jamais été porté à la connaissance de son
encadrante. Les notes consignent le motif~: la honte et la crainte d'un reproche
d'inattention. D'autre part, le contrôle s'adapte, mais individuellement et après coup. E1
contrôle désormais le processus et non plus le seul contenu final, demandant ce qui relève du
collaborateur, ce qui relève de l'outil et si les sources ont été vérifiées. E3 a formalisé
pour lui-même un contrôle en trois temps~: cohérence interne, contrôle croisé des sources,
test de défendabilité devant le client. E2, qui n'a pas vécu d'incident marquant, indique ne
pas contrôler différemment un contenu assisté.
```

*Pourquoi* : coupe deux phrases de 52 et 67 mots et remplace le cadratin par le deux-points qui introduit réellement les trois temps du protocole.

---
**11 — RECOMMANDÉ — `chapters/chapitre4.tex` — page 43**

*AVANT* :
```latex
Le silence est lui-même documenté, dans des termes
presque identiques et sans concertation~: J1 note que tout le monde utilise l'outil et que
personne ne le dit, et rattache ce silence à la crainte du reproche de ne plus réfléchir~; J2
emploie l'expression de «~secret de polichinelle~». Ce non-dit interne, codé en T3.1, n'était
pas anticipé --- la grille prévoyait l'opacité vis-à-vis du client, non la dissimulation
entre collègues.
```

*APRÈS* :
```latex
Le silence est lui-même documenté, dans des termes
presque identiques et sans concertation~: J1 note que tout le monde utilise l'outil et que
personne ne le dit, et rattache ce silence à la crainte du reproche de ne plus réfléchir. J2
emploie l'expression de «~secret de polichinelle~». Ce non-dit interne, codé en T3.1, n'était
pas anticipé. La grille prévoyait l'opacité vis-à-vis du client, non la dissimulation
entre collègues.
```

*Pourquoi* : coupe une phrase de 47 mots et supprime un cadratin, la précision sur la grille tenant seule.

---
**12 — RECOMMANDÉ — `chapters/chapitre4.tex` — page 43**

*AVANT* :
```latex
E1, manager de dix ans,
n'utilise presque pas l'outil, se déclare plus rapide seul et emploie le terme de «~béquille~»
à propos des juniors~; E2, associé de vingt-cinq ans et sponsor de la practice
concernée, l'utilise quotidiennement et le décrit comme un «~accélérateur de compétence, pas
substitut~».
```

*APRÈS* :
```latex
E1, manager de dix ans,
n'utilise presque pas l'outil, se déclare plus rapide seul et emploie le terme de «~béquille~»
à propos des juniors. E2, associé de vingt-cinq ans et sponsor de la practice
concernée, l'utilise quotidiennement et le décrit comme un «~accélérateur de compétence, pas
substitut~».
```

*Pourquoi* : coupe une phrase de 47 mots ; l'opposition entre les deux encadrants se lit mieux en deux portraits successifs qu'en une seule période.

---
**13 — RECOMMANDÉ — `chapters/chapitre4.tex` — page 43**

*AVANT* :
```latex
Un dernier élément doit être signalé sans être tranché. Le chapitre~1 décrit un cadre
reposant sur un seul outil homologué~; or E2 précise ne jamais verser de données
confidentielles dans des outils non officiels, formulation qui suppose un recours à ces outils
pour les contenus qui ne le sont pas, et J1 déclare un usage officieux dont il doute que la
prudence qui l'accompagne soit générale. La règle n'est donc pas comprise de la même façon
selon la position occupée. Il ne s'agit pas de statuer sur la conformité de ces pratiques,
que le dispositif ne permet pas d'établir, mais de constater qu'un cadre diversement
interprété n'encadre pas.
```

*APRÈS* :
```latex
Un dernier élément doit être signalé sans être tranché. Le chapitre~1 décrit un cadre
reposant sur un seul outil homologué. Or E2 précise ne jamais verser de données
confidentielles dans des outils non officiels, formulation qui suppose un recours à ces outils
pour les contenus qui ne le sont pas. J1, lui, déclare un usage officieux dont il doute que
la prudence qui l'accompagne soit générale. La règle n'est donc pas comprise de la même façon
selon la position occupée. Le dispositif ne permet pas d'établir la conformité de ces
pratiques. Le constat porte sur autre chose~: un cadre diversement interprété n'encadre pas.
```

*Pourquoi* : coupe une phrase de 58 mots et convertit la seule tournure « il ne s'agit pas de X mais de Y » du chapitre en deux affirmations, formulées comme la cinquième limite page 49.

---
**14 — RECOMMANDÉ — `chapters/chapitre4.tex` — page 44**

*AVANT* :
```latex
Deux nuances font l'intérêt de la confrontation. Les répondants ont localisé la frontière, là
où l'expérimentation la donne pour peu visible --- mais par une méthode unique et coûteuse,
l'échec chiffré en minutes perdues puis mémorisé en règle personnelle. La localisation est
acquise~; elle a été payée cinq fois, séparément, par des personnes qui ignoraient que leurs
collègues avaient payé le même prix. Ensuite, cette frontière ne sépare pas les tâches faciles
des tâches difficiles, mais celles dont le résultat se vérifie par recoupement de celles qui
exigent un contexte non observé~: c'est la frontière de la sanctuarisation décrite en 4.1, et
les répondants n'ont donc pas construit deux règles mais une seule.
```

*APRÈS* :
```latex
Deux nuances font l'intérêt de la confrontation. Les répondants ont localisé la frontière, là
où l'expérimentation la donne pour peu visible. Mais la méthode est unique et coûteuse~:
l'échec chiffré en minutes perdues puis mémorisé en règle personnelle. La localisation est
acquise~; elle a été payée cinq fois, séparément, par des personnes qui ignoraient que leurs
collègues avaient payé le même prix. Ensuite, cette frontière ne sépare pas les tâches faciles
des tâches difficiles, mais celles dont le résultat se vérifie par recoupement de celles qui
exigent un contexte non observé. C'est la frontière de la sanctuarisation décrite en 4.1~:
les répondants n'ont donc pas construit deux règles mais une seule.
```

*Pourquoi* : supprime un cadratin en conservant le « mais » de contraste, et coupe la phrase de 50 mots qui suit.

---
**15 — RECOMMANDÉ — `chapters/chapitre4.tex` — page 44**

*AVANT* :
```latex
Un désalignement mérite enfin d'être noté~: là où Noy et Zhang \cite{noy2023} puis
\mbox{Brynjolfsson}, Li et Raymond \cite{brynjolfsson2025} montrent des gains concentrés sur les
moins expérimentés, le gain le plus élevé est ici déclaré par le répondant le plus ancien, la
variable discriminante étant le portefeuille de tâches plutôt que le grade.
```

*APRÈS* :
```latex
Un désalignement mérite enfin d'être noté. Là où Noy et Zhang \cite{noy2023} puis
\mbox{Brynjolfsson}, Li et Raymond \cite{brynjolfsson2025} montrent des gains concentrés sur les
moins expérimentés, le gain le plus élevé est ici déclaré par le répondant le plus ancien. La
variable discriminante est le portefeuille de tâches plutôt que le grade.
```

*Pourquoi* : 50 mots ramenés à trois phrases, la conclusion sur la variable discriminante étant posée seule.

---
**16 — RECOMMANDÉ — `chapters/chapitre4.tex` — page 44**

*AVANT* :
```latex
Le cadre existant est un
cadre d'autorisation --- tel outil est permis, tel autre non --- et non un cadre de
vérification.
```

*APRÈS* :
```latex
Le cadre existant est un
cadre d'autorisation (tel outil est permis, tel autre non) et non un cadre de
vérification.
```

*Pourquoi* : deux cadratins pour une incise brève, que les parenthèses portent sans casser l'opposition finale.

---
**17 — RECOMMANDÉ — `chapters/chapitre4.tex` — page 44**

*AVANT* :
```latex
Le protocole en trois temps d'E3 est exactement un dispositif de
ce type, et la règle qu'il transmet aux juniors --- «~si tu peux pas justifier, mets pas~» ---
en est la maxime. Ce dispositif existe donc, il est fin et efficace~; mais il est privé,
```

*APRÈS* :
```latex
Le protocole en trois temps d'E3 est exactement un dispositif de
ce type. La règle qu'il transmet aux juniors en est la maxime~:
«~si tu peux pas justifier, mets pas~». Ce dispositif existe donc, il est fin et efficace~;
mais il est privé,
```

*Pourquoi* : deux cadratins supprimés en déplaçant le fragment cité en fin de phrase, où il porte plus.

---
**18 — RECOMMANDÉ — `chapters/chapitre4.tex` — page 45**

*AVANT* :
```latex
Or la nature des erreurs a changé --- E1
relève que celles de l'outil sont plus subtiles que les erreurs humaines --- sans que le
contenu de la qualification ait suivi.
```

*APRÈS* :
```latex
Or la nature des erreurs a changé (E1
relève que celles de l'outil sont plus subtiles que les erreurs humaines) sans que le
contenu de la qualification ait suivi.
```

*Pourquoi* : le renvoi à E1 est une incise justificative, que les parenthèses signalent mieux que deux cadratins dans une phrase déjà articulée sur « sans que ».

---
**19 — RECOMMANDÉ — `chapters/chapitre4.tex` — page 45**

*AVANT* :
```latex
J1, qui a pourtant toutes les raisons de noircir le tableau puisqu'il est
celui qui parle d'«~illusion de compétence~», décrit sa première proposition commerciale
comme un moment de formation fait de commentaires de titres et de structure, et observe que
ces commentaires portent aujourd'hui sur la solidité du raisonnement. E1 décrit
symétriquement ce que transmet une relecture --- le jugement, la raison pour laquelle un
chiffre est suspect --- et l'estime plus importante encore avec l'outil.
```

*APRÈS* :
```latex
J1 a pourtant toutes les raisons de noircir le tableau, puisqu'il est
celui qui parle d'«~illusion de compétence~». Il décrit sa première proposition commerciale
comme un moment de formation fait de commentaires de titres et de structure, et observe que
ces commentaires portent aujourd'hui sur la solidité du raisonnement. E1 décrit
symétriquement ce que transmet une relecture (le jugement, la raison pour laquelle un
chiffre est suspect) et l'estime plus importante encore avec l'outil.
```

*Pourquoi* : la relative de 50 mots devient deux phrases, et les deux cadratins de l'incise sur E1 passent en parenthèses.

---
**20 — RECOMMANDÉ — `chapters/chapitre4.tex` — page 45**

*AVANT* :
```latex
La forme étant déléguée, la revue se reporte sur ce qu'elle n'atteignait
auparavant qu'après plusieurs itérations --- la justification, la pertinence, la source. La
socialisation ne se réduit pas~; elle porte sur un objet de rang supérieur. Et ce qu'E1 décrit
--- énoncer ce qui rend un chiffre suspect, ce qui doit être vérifié et pourquoi --- relève
moins de la socialisation que de l'externalisation, conversion du tacite vers l'explicite~:
```

*APRÈS* :
```latex
La forme étant déléguée, la revue se reporte sur ce qu'elle n'atteignait
auparavant qu'après plusieurs itérations~: la justification, la pertinence, la source. La
socialisation ne se réduit pas~; elle porte sur un objet de rang supérieur. Et ce qu'E1 décrit
(énoncer ce qui rend un chiffre suspect, ce qui doit être vérifié et pourquoi) relève
moins de la socialisation que de l'externalisation, conversion du tacite vers l'explicite~:
```

*Pourquoi* : trois cadratins dans quatre lignes ; le premier introduit une énumération et devient un deux-points, les deux autres encadrent une incise et deviennent des parenthèses.

---
**21 — RECOMMANDÉ — `chapters/chapitre4.tex` — page 46**

*AVANT* :
```latex
Il coexiste ensuite avec une perte en amont que le même E1 signale, le chemin de réflexion
initial n'étant plus parcouru --- ce qui affecte l'internalisation, conversion de l'explicite
vers le tacite qui suppose l'exécution.
```

*APRÈS* :
```latex
Il coexiste ensuite avec une perte en amont que le même E1 signale, le chemin de réflexion
initial n'étant plus parcouru. Cette perte affecte l'internalisation, conversion de
l'explicite vers le tacite qui suppose l'exécution.
```

*Pourquoi* : le cadratin portait une conséquence, qui se dit en une phrase autonome.

---
**22 — RECOMMANDÉ — `chapters/chapitre4.tex` — page 46**

*AVANT* :
```latex
Exécuter manuellement
une fois avant d'accélérer est la condition d'internalisation~: sans exécution, le savoir
explicite déposé dans les méthodologies ne se convertit pas en savoir tacite, et le
professionnel se retrouve dans la situation, nommée en B4.2, de valider un contenu qu'il
n'aurait pas su produire.
```

*APRÈS* :
```latex
Exécuter manuellement
une fois avant d'accélérer est la condition d'internalisation. Sans exécution, le savoir
explicite déposé dans les méthodologies ne se convertit pas en savoir tacite. Le
professionnel se retrouve alors dans la situation, nommée en B4.2, de valider un contenu
qu'il n'aurait pas su produire.
```

*Pourquoi* : 46 mots ramenés à trois phrases, la thèse, le mécanisme, la conséquence.

---
**23 — RECOMMANDÉ — `chapters/chapitre4.tex` — page 46**

*AVANT* :
```latex
Les cinq répondants situent spontanément la valeur future du
cabinet là où Abbott place le noyau défendable d'une juridiction, dans l'inférence plutôt que
dans la collecte ou la mise en forme, et ceux qui refusent de mentionner l'outil au client
protègent un signal plutôt qu'une information, ce qui rejoint la lecture d'Alvesson
\cite{alvesson2001}. Mais cette convergence a été obtenue sur une question projective à dix
ans, dont la forme appelle une réponse valorisante. Les registres de Suchman permettent de
classer ce qui a été dit~: le registre cognitif est documenté par les cinq, chacun rapportant
la confiance du client à la fiabilité et à la maîtrise du domaine~; le moral l'est par trois,
par la responsabilité assumée devant le client, à quoi s'ajoute la non-déclaration de
l'usage, qui porte sur ce qui a été réellement fait et par qui~; le pragmatique n'est
documenté qu'une fois.
```

*APRÈS* :
```latex
Les cinq répondants situent spontanément la valeur future du
cabinet là où Abbott place le noyau défendable d'une juridiction, dans l'inférence plutôt que
dans la collecte ou la mise en forme. Ceux qui refusent de mentionner l'outil au client
protègent un signal plutôt qu'une information, ce qui rejoint la lecture d'Alvesson
\cite{alvesson2001}. Mais cette convergence a été obtenue sur une question projective à dix
ans, dont la forme appelle une réponse valorisante. Les registres de Suchman permettent de
classer ce qui a été dit. Le registre cognitif est documenté par les cinq, chacun rapportant
la confiance du client à la fiabilité et à la maîtrise du domaine. Le moral l'est par trois,
par la responsabilité assumée devant le client, à quoi s'ajoute la non-déclaration de
l'usage, qui porte sur ce qui a été réellement fait et par qui. Le pragmatique n'est
documenté qu'une fois.
```

*Pourquoi* : deux phrases de 52 et 72 mots coupées ; les trois registres de Suchman se lisent comme trois constats séparés.

---
**24 — RECOMMANDÉ — `chapters/chapitre4.tex` — page 46**

*AVANT* :
```latex
Interrogés
séparément sur la décision qu'ils prendraient à la place de la direction, les cinq répondants
ont convergé sans s'être parlé et sur le même point d'équilibre --- aucun ne demande
d'interdiction, tous demandent que la vérification soit organisée, et E1 et E3 y ajoutent la
traçabilité des contenus produits avec assistance.
```

*APRÈS* :
```latex
Interrogés
séparément sur la décision qu'ils prendraient à la place de la direction, les cinq répondants
ont convergé sans s'être parlé et sur le même point d'équilibre. Aucun ne demande
d'interdiction, tous demandent que la vérification soit organisée, et E1 et E3 y ajoutent la
traçabilité des contenus produits avec assistance.
```

*Pourquoi* : 51 mots coupés en deux ; le contenu du point d'équilibre gagne à ouvrir sa propre phrase.

---
**25 — RECOMMANDÉ — `chapters/chapitre4.tex` — page 47**

*AVANT* :
```latex
Chaque type de mission identifie une liste courte de tâches fondatrices --- plan de livrable,
synthèse d'un corpus documentaire, chiffrage, note de cadrage --- que le collaborateur produit
une fois sans assistance, la production étant relue et validée comme telle. Le passage est
acté~; l'usage de l'outil est ensuite non seulement autorisé mais encouragé sur ces mêmes
tâches, conformément à la séquence décrite par E2. La mesure doit se présenter comme une
séquence et non comme une restriction, faute de quoi elle produira les contournements
qu'anticipe la littérature sur les interventions organisationnelles \cite{venkatesh2008}~:
une règle vécue comme bridante sur une population déjà équipée est contournée en silence, et
le cabinet perd à la fois la formation et l'information.
```

*APRÈS* :
```latex
Chaque type de mission identifie une liste courte de tâches fondatrices (plan de livrable,
synthèse d'un corpus documentaire, chiffrage, note de cadrage) que le collaborateur produit
une fois sans assistance, la production étant relue et validée comme telle. Le passage est
acté~; l'usage de l'outil est ensuite non seulement autorisé mais encouragé sur ces mêmes
tâches, conformément à la séquence décrite par E2. La mesure doit se présenter comme une
séquence et non comme une restriction, faute de quoi elle produira les contournements
qu'anticipe la littérature sur les interventions organisationnelles \cite{venkatesh2008}.
Une règle vécue comme bridante sur une population déjà équipée est contournée en silence, et
le cabinet perd à la fois la formation et l'information.
```

*Pourquoi* : la liste de tâches passe en parenthèses, et la phrase de 52 mots est coupée après la référence.

---
**26 — RECOMMANDÉ — `chapters/chapitre4.tex` — page 47**

*AVANT* :
```latex
Le dispositif doit être déclaratif et non détectif~: il ne s'agit pas
de rechercher l'usage, mais de permettre de le signaler. Il doit être non punitif et énoncé
comme tel, faute de quoi il renforcera le non-dit interne au lieu de le lever --- le silence
actuel est motivé par la crainte du reproche, et un marquage perçu comme un aveu produirait
l'effet inverse.
```

*APRÈS* :
```latex
Le dispositif doit être déclaratif et non détectif~: il sert à
signaler l'usage, non à le rechercher. Il doit être non punitif et énoncé
comme tel, faute de quoi il renforcera le non-dit interne au lieu de le lever. Le silence
actuel est motivé par la crainte du reproche, et un marquage perçu comme un aveu produirait
l'effet inverse.
```

*Pourquoi* : la seconde tournure « il ne s'agit pas de X mais de Y » devient une affirmation, et la phrase de 45 mots qui suit est coupée après « lever ».

---
**27 — RECOMMANDÉ — `chapters/chapitre4.tex` — pages 47–48**

*AVANT* :
```latex
Quatre des cinq demandent une formation, et tous précisent qu'elle ne doit pas porter sur la
manipulation de l'outil~: J1 la veut sur la détection des erreurs, le risque n'étant pas que
l'outil se trompe mais que le consultant ne le voie pas~; E1 veut que les encadrants soient
formés à une relecture spécifique, les erreurs de l'outil étant plus subtiles~; E2 la range du
côté de la compétence et non de la défiance~; E3 la veut obligatoire. Le cabinet n'a pas à en
concevoir le contenu, lequel existe déjà sous forme privée dans le corpus~: le protocole en
trois temps d'E3 est un standard éprouvé et transmissible en une page, que complète la
pratique de J1 consistant à conserver une source de vérité indépendante à côté du document en
production. La mesure consiste à expliciter ce savoir tacite --- rassembler les protocoles
individuels, les formaliser, les enseigner.
```

*APRÈS* :
```latex
Quatre des cinq demandent une formation, et tous précisent qu'elle ne doit pas porter sur la
manipulation de l'outil. J1 la veut sur la détection des erreurs, le risque n'étant pas que
l'outil se trompe mais que le consultant ne le voie pas. E1 veut que les encadrants soient
formés à une relecture spécifique, les erreurs de l'outil étant plus subtiles. E2 la range du
côté de la compétence et non de la défiance~; E3 la veut obligatoire. Le cabinet n'a pas à en
concevoir le contenu, lequel existe déjà sous forme privée dans le corpus. Le protocole en
trois temps d'E3 est un standard éprouvé et transmissible en une page, que complète la
pratique de J1 consistant à conserver une source de vérité indépendante à côté du document en
production. La mesure consiste à expliciter ce savoir tacite~: rassembler les protocoles
individuels, les formaliser, les enseigner.
```

*Pourquoi* : coupe deux phrases de 78 et 53 mots et remplace un cadratin d'énumération par un deux-points ; le point-virgule entre E2 et E3, qui joint deux propositions courtes, est conservé.

---
**28 — RECOMMANDÉ — `chapters/chapitre4.tex` — page 48**

*AVANT* :
```latex
Le corpus
l'établit deux fois --- les encadrants qui ont modifié leur revue l'ont fait après un incident
vécu, et le seul quasi-incident rapporté par un junior n'est jamais remonté. Deux mesures en
découlent. La première est un traitement organisé des quasi-incidents, dissocié de toute
conséquence individuelle~: un incident détecté avant le client est une information de valeur,
sa remontée doit être plus avantageuse que son silence, et les cas recueillis alimentent la
révision périodique du protocole de vérification, de sorte que l'apprentissage cesse de
dépendre de la répartition aléatoire des incidents.
```

*APRÈS* :
```latex
Le corpus
l'établit deux fois~: les encadrants qui ont modifié leur revue l'ont fait après un incident
vécu, et le seul quasi-incident rapporté par un junior n'est jamais remonté. Deux mesures en
découlent. La première est un traitement organisé des quasi-incidents, dissocié de toute
conséquence individuelle. Un incident détecté avant le client est une information de valeur,
et sa remontée doit être plus avantageuse que son silence. Les cas recueillis alimentent la
révision périodique du protocole de vérification, de sorte que l'apprentissage cesse de
dépendre de la répartition aléatoire des incidents.
```

*Pourquoi* : le cadratin annonçait deux preuves et devient un deux-points ; la phrase de 58 mots qui décrit la mesure est coupée en trois.

---
**29 — RECOMMANDÉ — `chapters/chapitre4.tex` — page 48**

*AVANT* :
```latex
Cette évolution est enfin cohérente avec le repositionnement que
les cinq décrivent déjà --- la valeur vendue se déplace vers le jugement et la responsabilité
assumée \cite{suchman1995} --- car un dispositif de vérification explicite est ce qui rend
cette promesse vérifiable.
```

*APRÈS* :
```latex
Cette évolution est enfin cohérente avec le repositionnement que
les cinq décrivent déjà (la valeur vendue se déplace vers le jugement et la responsabilité
assumée \cite{suchman1995}), car un dispositif de vérification explicite est ce qui rend
cette promesse vérifiable.
```

*Pourquoi* : l'incise porte le contenu du repositionnement et se met entre parenthèses, la causale finale retrouvant sa virgule.

---
**30 — RECOMMANDÉ — `chapters/chapitre4.tex` — page 48**

*AVANT* :
```latex
Un constat dit saturé signifie que les cinq récits le documentent, non qu'il
est répandu dans la practice~; un constat dit clivant oppose des répondants nommément
identifiés, non deux groupes constitués, et le clivage sur l'adaptation de la revue passe à
l'intérieur du groupe des encadrants.
```

*APRÈS* :
```latex
Un constat dit saturé signifie que les cinq récits le documentent, non qu'il
est répandu dans la practice. Un constat dit clivant oppose des répondants nommément
identifiés, non deux groupes constitués, et le clivage sur l'adaptation de la revue passe à
l'intérieur du groupe des encadrants.
```

*Pourquoi* : les deux définitions sont parallèles et se lisent mieux en deux phrases qu'en une de 46 mots.

---
**31 — RECOMMANDÉ — `chapters/chapitre4.tex` — page 48**

*AVANT* :
```latex
La deuxième tient à l'inégale solidité des axes. L'axe C est le plus mince et porte pourtant
la troisième question directrice~: un seul répondant rapporte une interpellation réelle par un
client, un seul une conséquence commerciale documentée, le reste étant du déclaratif projectif
recueilli sur des questions dont la forme appelle une réponse valorisante. La convergence
obtenue sur cet axe est donc d'une autre nature que celle obtenue sur les axes A et D, où elle
repose sur des récits d'incidents datés et chiffrés~: elle dit ce que le métier devrait être,
non comment la légitimité se reconstruit devant un client.
```

*APRÈS* :
```latex
La deuxième tient à l'inégale solidité des axes. L'axe C est le plus mince et porte pourtant
la troisième question directrice. Un seul répondant rapporte une interpellation réelle par un
client, un seul une conséquence commerciale documentée. Le reste est du déclaratif projectif,
recueilli sur des questions dont la forme appelle une réponse valorisante. La convergence
obtenue sur cet axe est donc d'une autre nature que celle obtenue sur les axes A et D, où elle
repose sur des récits d'incidents datés et chiffrés. Elle dit ce que le métier devrait être,
non comment la légitimité se reconstruit devant un client.
```

*Pourquoi* : deux phrases de 46 et 47 mots coupées, dans une section de limites où l'affirmation courte porte davantage.

---
**32 — RECOMMANDÉ — `chapters/chapitre4.tex` — page 49**

*AVANT* :
```latex
Cette position a probablement rendu possible le recueil
du non-dit codé en T3.1 --- un enquêteur extérieur n'aurait guère obtenu de deux juniors
l'aveu d'un usage dissimulé à leur hiérarchie --- mais elle expose au risque symétrique de
reconnaître d'autant plus aisément un phénomène qu'on s'attendait à trouver.
```

*APRÈS* :
```latex
Cette position a probablement rendu possible le recueil
du non-dit codé en T3.1~: un enquêteur extérieur n'aurait guère obtenu de deux juniors
l'aveu d'un usage dissimulé à leur hiérarchie. Mais elle expose au risque symétrique de
reconnaître d'autant plus aisément un phénomène qu'on s'attendait à trouver.
```

*Pourquoi* : les deux derniers cadratins du chapitre disparaissent et la phrase de 46 mots se coupe sur le « mais », qui ouvre le risque symétrique.

---

## Tableau récapitulatif

| N° | Degré | Fichier | Page | Défaut traité |
|---|---|---|---|---|
| 1 | RECOMMANDÉ | `chapitre4.tex` | 39 | cadratin + phrase 46 mots |
| 2 | RECOMMANDÉ | `chapitre4.tex` | 39–40 | 2 cadratins + phrase 91 mots |
| 3 | RECOMMANDÉ | `chapitre4.tex` | 40 | phrase 83 mots |
| 4 | RECOMMANDÉ | `chapitre4.tex` | 40 | cadratin + phrase 64 mots |
| 5 | RECOMMANDÉ | `chapitre4.tex` | 40–41 | phrases 54 et 60 mots |
| 6 | RECOMMANDÉ | `chapitre4.tex` | 41 | phrase 75 mots |
| 7 | RECOMMANDÉ | `chapitre4.tex` | 41 | cadratin + phrase 49 mots |
| 8 | RECOMMANDÉ | `chapitre4.tex` | 42 | phrase 60 mots |
| 9 | RECOMMANDÉ | `chapitre4.tex` | 42 | 2 cadratins + phrase 46 mots |
| 10 | RECOMMANDÉ | `chapitre4.tex` | 43 | cadratin + phrases 52 et 67 mots |
| 11 | RECOMMANDÉ | `chapitre4.tex` | 43 | cadratin + phrase 47 mots |
| 12 | RECOMMANDÉ | `chapitre4.tex` | 43 | phrase 47 mots |
| 13 | RECOMMANDÉ | `chapitre4.tex` | 43 | phrase 58 mots + « il ne s'agit pas de… mais de… » |
| 14 | RECOMMANDÉ | `chapitre4.tex` | 44 | cadratin + phrase 50 mots |
| 15 | RECOMMANDÉ | `chapitre4.tex` | 44 | phrase 50 mots |
| 16 | RECOMMANDÉ | `chapitre4.tex` | 44 | 2 cadratins |
| 17 | RECOMMANDÉ | `chapitre4.tex` | 44 | 2 cadratins |
| 18 | RECOMMANDÉ | `chapitre4.tex` | 45 | 2 cadratins |
| 19 | RECOMMANDÉ | `chapitre4.tex` | 45 | 2 cadratins + phrase 50 mots |
| 20 | RECOMMANDÉ | `chapitre4.tex` | 45 | 3 cadratins |
| 21 | RECOMMANDÉ | `chapitre4.tex` | 46 | cadratin |
| 22 | RECOMMANDÉ | `chapitre4.tex` | 46 | phrase 46 mots |
| 23 | RECOMMANDÉ | `chapitre4.tex` | 46 | phrases 52 et 72 mots |
| 24 | RECOMMANDÉ | `chapitre4.tex` | 46 | cadratin + phrase 51 mots |
| 25 | RECOMMANDÉ | `chapitre4.tex` | 47 | 2 cadratins + phrase 52 mots |
| 26 | RECOMMANDÉ | `chapitre4.tex` | 47 | cadratin + phrase 45 mots + « il ne s'agit pas de… mais de… » |
| 27 | RECOMMANDÉ | `chapitre4.tex` | 47–48 | cadratin + phrases 78 et 53 mots |
| 28 | RECOMMANDÉ | `chapitre4.tex` | 48 | cadratin + phrase 58 mots |
| 29 | RECOMMANDÉ | `chapitre4.tex` | 48 | 2 cadratins |
| 30 | RECOMMANDÉ | `chapitre4.tex` | 48 | phrase 46 mots |
| 31 | RECOMMANDÉ | `chapitre4.tex` | 48 | phrases 46 et 47 mots |
| 32 | RECOMMANDÉ | `chapitre4.tex` | 49 | 2 cadratins + phrase 46 mots |

## Décompte des `---`

**36 occurrences relevées, 32 traitées, 4 restantes.** Les quatre restantes sont les
titres de sous-section, hors périmètre :

| Ligne | Texte |
|---|---|
| 66 | `\subsection{Axe A --- L'appropriation des outils}` |
| 118 | `\subsection{Axe B --- Apprentissage et transmission}` |
| 148 | `\subsection{Axe C --- Légitimité et relation client}` |
| 168 | `\subsection{Axe D --- Gouvernance, contrôle et risques}` |

Aucun `---` du fichier ne se trouve à l'intérieur d'un `tabular` : le tableau 4.1 n'utilise
que des `\hline`. L'exception prévue ne s'applique donc pas ici.

## Points à trancher

1. **Les quatre cadratins de titres.** Ils sont hors périmètre par la règle « ne pas toucher
   aux titres de section », mais ils sont bien des cadratins et le même motif se répète dans
   les titres des autres chapitres. Faut-il les laisser tels quels, ou les traiter à part et
   de façon homogène sur tout le document, par exemple en deux-points (« Axe A : l'appropriation
   des outils ») ? Un changement de titre déplace la table des matières détaillée et impose
   une recompilation de contrôle.

2. **Les deux occurrences de « considérable » ne sont pas dans ce fichier.** Elles se
   trouvent en `chapitre1.tex` ligne 181 (« dont le volume peut être considérable ») et en
   `chapitre2.tex` ligne 331 (« considérable~: le problème posé par les productions
   erronées… »). Faut-il les traiter dans une passe distincte sur ces deux fichiers ?

3. **La troisième tournure « il ne s'agit pas de X mais de Y » est en `conclusion.tex`**,
   ligne 84 (« s'agit pas de rechercher l'usage, mais de permettre de le déclarer sans
   coût »). Elle reprend celle de la correction n° 26 ; si celle-ci est appliquée, faut-il
   aligner la conclusion sur la même formulation affirmative ?

4. **Trois amorces courtes ont été introduites pour couper sans perdre l'annonce** que
   portait le deux-points ou le cadratin : « Le déplacement est chiffré~: » (n° 4), « Les
   notes consignent le motif~: » (n° 10) et « Le constat porte sur autre chose~: » (n° 13).
   Elles n'ajoutent aucune information au-delà de ce que la phrase d'origine annonçait, mais
   elles sont de moi et non du matériau : à valider.

5. **« E3 la juge non pas dissimulatrice mais contre-productive » page 42** est une antithèse
   de la même famille que celles visées par la consigne, mais elle rapporte un jugement
   attribué à un répondant, ce qui interdit d'y toucher sans risquer le sens. Non corrigée :
   confirmer qu'elle reste.

## Contrôles de non-régression

Les trente-deux corrections ont été appliquées à une copie de travail, puis mesurées :

- `---` : 36 → 4, toutes dans des titres de sous-section.
- Phrases de plus de 45 mots : 30 → 0. *(Le décompte de trente-quatre annoncé en consigne
  suppose une règle de comptage différente — vraisemblablement les mots liés par `~` ou par
  trait d'union comptés séparément. Le résultat est le même : il n'en reste aucune.)*
- `\cite` (18), `\ref` (1), `\label` (1), `\textbf` (6) : identiques, à l'unité et au contenu.
- Les 21 fragments entre guillemets `«~…~»` : identiques caractère pour caractère.
- Les 28 codes de grille, les 84 codes de répondants et les 47 nombres du fichier :
  identiques.
- Le contenu du `tabular` du tableau 4.1 : inchangé.
- Aucun `«~…~»` n'est coupé par un saut de ligne du source qui ne l'était pas déjà.

**Aucun fichier n'a été modifié.** La copie de travail a servi aux seules mesures ci-dessus.
