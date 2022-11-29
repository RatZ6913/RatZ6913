<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <div id="compteur">0</div>

    <pre id="poeme">
        Possèdent pour… leur vie est douce, bonne et grasse !
        Qu'ils sont patriarcaux, béats, vermillonnés,
        Cinq pour cent ! Quel bonheur de dormir dans sa crasse,
        De ne pas voir plus loin que le bout de son nez !
        
        N'avoir aucun besoin de baiser sur les lèvres,
        Et, loin des songes vains, loin des soucis cuisants,
        Posséder pour tout cœur un viscère sans fièvres,
        Un coucou régulier et garanti dix ans !
        
        Oh ! les gens bienheureux !... Tout à coup, dans l'espace,
        Si haut qu'il semble aller lentement, un grand vol
        En forme de triangle arrive, plane et passe.
        Où vont-ils ? Qui sont-ils ? Comme ils sont loin du sol !
        
        Les pigeons, le bec droit, poussent un cri de flûte
        Qui brise les soupirs de leur col redressé,
        Et sautent dans le vide avec une culbute.
        Les dindons d'une voix tremblotante ont gloussé.
        
        Les poules picorant ont relevé la tête.
        Le coq, droit sur l'ergot, les deux ailes pendant,
        Clignant de l'œil en l'air et secouant la crête,
        Vers les hauts pèlerins pousse un appel strident.
        
        Qu'est-ce que vous avez, bourgeois ? soyez donc calmes.
        Pourquoi les appeler, sot ? Ils n'entendront pas.
        Et d'ailleurs, eux qui vont vers le pays des palmes,
        Crois-tu que ton fumier ait pour eux des appas ?
        
        Regardez-les passer ! Eux, ce sont les sauvages.
        Ils vont où leur désir le veut, par-dessus monts,
        Et bois, et mers, et vents, et loin des esclavages.
        L'air qu'ils boivent ferait éclater vos poumons.
        
        Regardez-les ! Avant d'atteindre sa chimère,
        Plus d'un, l'aile rompue et du sang plein les yeux,
        Mourra. Ces pauvres gens ont aussi femme et mère,
        Et savent les aimer aussi bien que vous, mieux.
        
        Pour choyer cette femme et nourrir cette mère,
        Ils pouvaient devenir volaille comme vous.
        Mais ils sont avant tout les fils de la chimère,
        Des assoiffés d'azur, des poètes, des fous.
        
        Ils sont maigres, meurtris, las, harassés. Qu'importe !
        Là-haut chante pour eux un mystère profond.
        A l'haleine du vent inconnu qui les porte
        Ils ont ouvert sans peur leurs deux ailes. Ils vont.
        
        La bise contre leur poitrail siffle avec rage.
        L'averse les inonde et pèse sur leur dos.
        Eux, dévorent l'abîme et chevauchent l'orage.
        Ils vont, loin de la terre, au dessus des badauds.
        
        Ils vont, par l'étendue ample, rois de l'espace.
        Là-bas, ils trouveront de l'amour, du nouveau.
        Là-bas, un bon soleil chauffera leur carcasse
        Et fera se gonfler leur cœur et leur cerveau.
        
        Là-bas, c'est le pays de l'étrange et du rêve,
        C'est l'horizon perdu par delà les sommets,
        C'est le bleu paradis, c'est la lointaine grève
        Où votre espoir banal n'abordera jamais.
        
        Regardez-les, vieux coq, jeune oie édifiante !
        Rien de vous ne pourra monter aussi haut qu'eux.
        Et le peu qui viendra d'eux à vous, c'est leur fiente.
        Les bourgeois sont troublés de voir passer les gueux.
        </pre>

</body>
</html>


#### First part
L'idée ici est de retracer les étapes qu'aurait effectuées Georges Brassens pour mettre en chanson le poème 'Les oiseaux de passage' de Jean Richepin.

Voici les étapes à effectuer :
* créer un nouveau dépôt Git.
* le poème de Richepin est situé dans le fichier html index.html

Appropriez vous le challenge sur vos machines.
**Créer une branche nommée _FirstPart_votreNom_.**

Modifications à valider :
1. [ ] suppression des 8 premiers paragraphes (jusque "...épiciers?")
2. [ ] suppression du §4 courant ("Elle ne sentit...")
3. [ ] suppression du §5 courant ("Aussi, comme...")
4. [ ] modifications du §5 courant (en 2 commits séparés) :
    1. [ ] N'avoir aucun... -> Ils n'ont aucun... (Le premier)
    2. [ ] Posséder pour... -> Possèdent pour… (Le deuxième)
5. [ ] suppression § 7, 8 et 9 courants (de "Les pigeons, le bec..." à "...des appas ?")
6. [ ] suppression § 10, 11, 12 et 13 courants (de "Ils sont maigres..." à "...n'abordera jamais.")
7. [ ] répétition du dernier §

**La branche _FirstPart_votreNom_ permettra la correction de ce que vous avez fait**


Usez et abusez de git status, git diff, git log et git show à chaque étape pour bien comprendre ce qu'il se passe !
Votre historique devrait ressembler à cela:
```
496067d répétition du dernier §
7458110 suppression § 10, 11, 12 et 13
0e779bd suppression § 7, 8 et 9
75ec3a0 §5: Posseder pour... -> Possèdent pour...
d0fc7a3 §5: N'avoir aucun... -> Ils n'ont aucun...
75f22cf suppression du §5 courant
3e81e34 suppression du §4 courant
4329040 Suppression des 8 premiers §
ca170fa Ajout du poème de Richepin
```
1. [ ] Effectuer un Push vers le serveur Origin.
2. [ ] Effectuons maintenant une Pull Request vers le serveur Upstream.
