# Blue November Research

Atelier AxoLab, UM6SS Rabat : lire un essai de dépistage et le situer dans une méta-analyse.

**Question.** Chez les hommes sans cancer de la prostate connu, l'invitation au dépistage par PSA,
par rapport à l'absence de dépistage organisé, réduit-elle la mortalité par cancer de la prostate ?

## Programme

| Durée | Étape | Ce que vous faites |
|---|---|---|
| 50 min | Session plénière | Suivez les [diapositives](slides.pdf) : types de revue, guides (PRISMA), bases de la méta-analyse, lecture critique d'un essai |
| 10 min | Présentation des thèmes | Formez 6 groupes ; chaque groupe reçoit un article (tableau ci-dessous) |
| 2 h | Analyse en groupe | Remplissez la fiche d'analyse remise par AxoLab, en suivant les consignes ci-dessous |
| 50 min | Restitution | Un représentant par groupe présente en 5 minutes ; les résultats sont combinés en direct |
| 10 min | Conclusion | Messages clés de l'atelier |

## Contenu

| Fichier | Rôle |
|---|---|
| [`slides.pdf`](slides.pdf) | Diapositives de la session plénière |
| [`fiche-recap.pdf`](fiche-recap.pdf) | Ce qu'il faut chercher, section par section |
| [`articles/`](articles/) | Les articles des groupes |

## Articles

| Groupe | Article | Fichier |
|---|---|---|
| Démo | Hugosson et al. Göteborg, *Lancet Oncol* 2010 | [PDF](articles/0-demo-goteborg-hugosson-2010.pdf) |
| 1 | Labrie et al. Québec, *Prostate* 2004 | [PDF](articles/groupe1-labrie-2004.pdf) |
| 2 | Lundgren et al. Stockholm, *J Urol* 2018 | [PDF](articles/groupe2-lundgren-2018.pdf) |
| 3 | Pinsky et al. PLCO, *Cancer* 2017 | [PDF](articles/groupe3-plco-pinsky-2017.pdf) |
| 4 | Schröder et al. ERSPC, *Lancet* 2014 | [PDF](articles/groupe4-erspc-schroder-2014.pdf) |
| 5 | Martin et al. CAP, *JAMA* 2018 | [PDF](articles/groupe5-cap-martin-2018.pdf) |
| 6 | Ilic et al. méta-analyse, *BMJ* 2018 | [PDF](articles/groupe6-ilic-2018.pdf) |

## Consignes pour l'analyse (2 heures)

1. Lisez votre article et remplissez la fiche d'analyse AxoLab, en vous aidant de la fiche récapitulative.
2. **Règle d'or** : chaque réponse cite la page de l'article. Pas de page, pas de réponse.
3. Relevez l'effet sur la mortalité par cancer de la prostate **tel qu'écrit dans l'article** :
   mesure (RR, HR, IRR), valeur et IC 95 %. Prenez l'analyse en intention de dépister.
4. Convertissez-le en effet absolu : combien de décès évités pour 1 000 hommes invités ?
5. Jugez le risque de biais avec RoB 2 simplifié (groupe 6 : AMSTAR 2).

## Restitution (5 minutes par groupe)

1. L'essai en une phrase.
2. L'effet sur la mortalité avec son IC 95 %, puis pour 1 000 hommes.
3. Le principal risque de biais.
4. Faut-il l'inclure dans la méta-analyse, et avec quel risque de biais ?

Les effets des groupes 1 à 5 sont ensuite combinés en direct dans une méta-analyse (R, package `meta`).
