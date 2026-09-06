# Assistant Brainstorming

Un objet tenu assez longtemps pour changer de forme : notion, dossier, brève, thèse adverse. Pas un genre. Un protocole.

Il n’ajoute rien que le mode conversation ne sache déjà faire. Il change *comment* on le fait. Cinq modalités. Un ordre de réflexion. Des formats que l’on peut réemployer. Des marqueurs pour que le fil ne pèse pas partout pareil.

Écrit pour Grok 4.2, repris pour Grok 4.6. Un seul coordinateur. Harper, Benjamin et Lucas restent des rôles internes — recherche, logique, divergence — jamais des instances, jamais des noms dans la sortie.

Fichier agent : `SKILL.md`.

---

## Pourquoi s’en servir

L’écriture et le billet ne sont qu’une porte. Le même ordre tient :

- l’**analyse stratégique** — options, contraintes, ce que l’on accepte encore de traiter ;
- le **débat polémique** — pesée, réfutation calibrée, ce qui reste debout ;
- la **culture générale** — un concept ouvert avant d’être recouvert de fiches ;
- le **suivi d’actualité** — un matériau lu, puis commenté ou confronté, sans noyade dans la revue de presse.

Autres portes, mêmes gonds : préparation d’un cours ou d’une démonstration, lecture critique d’un article, cadrage d’un projet technique, délibération éthique ou politique, veille thématique, note de décision, opposition structurée à un argument public.

Partout la même exigence. Ouvrir. Cadrer. Éprouver. Dans cet ordre.

### Recommandations

Choisir le mode selon le **geste**, non selon le sujet. Une actualité se commente. Une doctrine se développe. Une proposition se confronte. Une thèse adverse se réfute. Deux gestes dans le même tour, et le marqueur s’émousse.

Partir du concret ou de la notion, jamais les confondre. Un lien se lit. Un mot ne devient pas un dossier par magie.

Le réel filtre **après** le cadre. Chercher trop tôt, on accumule. Refuser le filtre, on rêve.

**Autre** sert à curer le fil, pas à penser à sa place. S’il devient le mode par défaut, les quatre autres ne pèsent plus.

Tenir le contrat. Ne pas recommencer le monde. Annoncer un changement de mode. Laisser une réfutation abaisser une thèse sans effacer le jalon.

---

## Ce que c’est

Trois temps, une intention nommée.

1. **Comprendre** le prompt et le contexte. Lien, article, document : consulter, préparer.
2. **Répondre** à l’intention et pousser plus loin.
3. **Mettre en forme** selon le mode.

Deux amorces. Les modes n’ont pas à copier la même silhouette.

- concrète — article, document, lien, extrait ;
- notionnelle — thème, sujet, notion, question sans corpus.

Divergences d’abord. Cadre ensuite. Le réel comme crible, pas comme substitut à la pensée. Inverser, c’est la revue de presse sans position, ou la variation qui ne veut pas rencontrer le monde.

## Ce que ce n’est pas

Pas Grok 4.20, pas Heavy, pas un colloque parallèle.
Pas Grok Bot, pas les sous-agents de Build.
Pas une machine à coefficients.
Pas un second cerveau.

---

## Modes

On nomme, ou le modèle choisit. Chaque réponse visible s’ouvre par **Mode : …**

| Mode | Geste | Forme |
| --- | --- | --- |
| **Commentaire** | Un point de vue, puis le réel | Fluide, sans plan apparent |
| **Développement** | Plan d’abord, collecte ensuite | Plan numéroté, transitions |
| **Confrontation** | Pesée | Forces, puis faiblesses, titres de versant |
| **Réfutation** | Attaque de ce qui a été tenu | Synthèse calibrée |
| **Autre** | Exception, consigne, curation | Court, rare |

L’ordre change la **substance**. Commenter après une veille large n’est pas développer après un plan. On ne joue pas au même jeu.

---

## Itération

Mode et but posés, on travaille le contrat déjà là.

Préciser le public, la date, la longueur, les sources exclues.
Poser des questions sans changer de but.
Resserrer une recherche une fois le cadre fixé.
Retirer un point qui ne porte plus.
Réfuter un point encore en vue.

Le monde n’est pas à reconstruire à chaque message. Un changement de mode s’annonce, puis on reprend l’ordre qui va avec.

---

## Curation du fil

Le modèle pondère déjà, en silence. Les modes peuvent devenir des **marqueurs**. Ils ne commandent pas le moteur.

Barème à activer en **Autre**, quand on veut le dire :

> Tiens le fil. À genre égal, le plus récent l’emporte. Un développement ou un commentaire dédié porte la thèse. Une confrontation garde les deux plateaux. Une réfutation abaisse la thèse, non le jalon. Un Autre nommé prime sur le barème.

Une idée réfutée pèse moins **si** le jalon reste visible.
Un point développé ou commenté reste plus disponible.
Une confrontation affine sans retirer un plateau.
**Autre** prime dès qu’il est nommé — et doit rester rare.

| Formule | Effet |
| --- | --- |
| À retenir. | Charge utile |
| Fil conducteur : … | Oriente la suite |
| Moins peser désormais. | Abaisse sans effacer |
| Réfuté ; ne plus relancer. | Ferme une piste |
| Incident clos. | Classe un écart |
| Rectification seule. | Corrige sans tout relire |
| Remplace X par Y. | Substitution |
| Périmètre / hors périmètre | Redessine le cadre |
| En attente de source. | Garde l’idée, retire sa force |
| Parc : y revenir plus tard. | Sort du tour, ne s’oublie pas |
| Aparté ; hors pondération. | Ce tour ne déplace rien |
| Consigne de forme seulement. | Ton, longueur, langue |
| Ne pas recommencer le monde. | Continuité |

Une formule par Autre. Deux, et le marqueur se brouille.

---

## Installation

```text
brainstorming/
├── SKILL.md      # chargé par l’agent
└── README.md     # le présent exposé
```

Copier vers les skills utilisateur :

```text
~/.grok/skills/brainstorming/
```

ou :

```text
/home/workdir/.grok/skills/brainstorming/
```

Le champ `description` du frontmatter déclenche le chargement. On dit `brainstorming`, `mode Assistant Brainstorming`, le nom d’un mode, on apporte un article, un thème, un document.

Pour **désactiver** : ne plus invoquer ; retirer ou renommer le dossier.

---

## Ce qui reste volontairement lâche

L’emboîtement des trois temps d’introduction et des trois temps de chaque mode.
La lecture d’un document fourni face à la collecte-filtre.
L’amorce notionnelle, plus déduite qu’écrite.

Ces jeux sont laissés à l’initiative. Le contrat tient sans eux : un mode nommé, un coordinateur, pas de troupe fictive.

L’étape 1 du `SKILL.md` est en style **déclaratif**. Plus lisible après une recharge à la main. Moins tentée de se faire découper comme une balise.

---

## Statut

Publié sur le dépôt dédié. L’agent obéit à `SKILL.md`. Ce README dit l’esprit, les usages et la doctrine de curation. Il n’est pas une instruction chargée.
